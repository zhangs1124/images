---
description: 雙編輯器比對工作流程 - 當改了很多不確定哪些正確時使用
---

# 🔄 雙編輯器比對工作流程

## 📋 使用時機

當你遇到以下情況時使用此流程：
- ✅ 改了很多程式碼，不確定哪些是正確的
- ✅ 需要一段一段測試才知道哪段是對的
- ✅ 想要同時看到「混合版本」和「乾淨版本」
- ✅ 需要在兩個編輯器中比對和複製程式碼

## 🎯 完整操作步驟

### 步驟 1：保存目前的混合版本

```powershell
# 在專案目錄中
cd d:\project\my-aspnet-project

# 保存所有改動到 Git
git add .
git commit -m "混合版本：包含所有改動（有些可能是錯的）"
```

**說明**：這一步把你目前的所有改動（包括正確和錯誤的）都保存到 Git，確保不會丟失。

---

### 步驟 2：手動複製專案資料夾

在檔案總管中：
1. 複製整個專案資料夾（例如：`d:\project\my-aspnet-project`）
2. 貼上到同一層目錄，重新命名為 `my-aspnet-project-mixed`

**結果**：
```
d:\project\
├─ my-aspnet-project\          ← 原專案（等下會還原成乾淨版本）
└─ my-aspnet-project-mixed\    ← 備份（保留混合版本）
```

---

### 步驟 3：還原原專案到乾淨版本

```powershell
# 在原專案目錄中
cd d:\project\my-aspnet-project

# 還原到上一個乾淨的 commit
git reset --hard HEAD~1
```

**說明**：現在原專案回到了「還沒加那些改動」的乾淨狀態。

---

### 步驟 4：開啟兩個 VS Code 視窗

```powershell
# 開啟第一個視窗（乾淨版本）
code d:\project\my-aspnet-project

# 開啟第二個視窗（混合版本）
code d:\project\my-aspnet-project-mixed
```

**或者**：
- 在檔案總管中，右鍵點擊資料夾 → 「以 Code 開啟」

---

### 步驟 5：一段一段複製和測試

#### 5.1 複製第一段程式碼

在兩個視窗中：
- **視窗 1（乾淨版本）**：打開 `Controllers/HomeController.cs`
- **視窗 2（混合版本）**：打開 `Controllers/HomeController.cs`

從視窗 2 複製 `Action1` 的程式碼到視窗 1。

#### 5.2 測試

在視窗 1（乾淨版本）中：
1. 按 `F5` 執行專案
2. 測試 `Action1` 是否正常運作

#### 5.3 如果測試通過，立即 Commit

```powershell
# 在視窗 1（乾淨版本）的終端機中
cd d:\project\my-aspnet-project
git add Controllers/HomeController.cs
git commit -m "新增 Action1（已測試通過）"
```

#### 5.4 繼續複製下一段

重複步驟 5.1 - 5.3：
- 複製 `Action2`
- 測試
- 如果通過，commit
- 複製 `Action3`（如果需要修正，先修正再測試）
- 測試
- 如果通過，commit

---

### 步驟 6：完成後刪除備份資料夾

當所有正確的程式碼都複製並測試完成後：

1. 關閉視窗 2（混合版本）
2. 在檔案總管中刪除 `d:\project\my-aspnet-project-mixed` 資料夾

---

### 步驟 7：推送到 GitHub（可選）

```powershell
# 在原專案中
cd d:\project\my-aspnet-project
git push origin main
```

---

## 💡 重要提示

### ✅ 優點

1. **安全**：混合版本有備份，不怕丟失
2. **清楚**：可以同時看到兩個版本
3. **靈活**：可以一段一段測試
4. **有記錄**：每測試通過一段就 commit，有完整歷史

### ⚠️ 注意事項

1. **記得 commit**：每測試通過一段就要 commit
2. **記得刪除備份**：完成後要刪除備份資料夾，避免佔用空間
3. **不要在備份資料夾中改動**：備份只用來「查看」和「複製」，不要在裡面修改

---

## 🎯 快速參考

### 快速指令

```powershell
# 1. 保存混合版本
git add .
git commit -m "混合版本"

# 2. 手動複製資料夾（在檔案總管中操作）

# 3. 還原乾淨版本
git reset --hard HEAD~1

# 4. 開兩個 VS Code
code .
code ..\my-project-mixed

# 5. 每測試通過一段就 commit
git add .
git commit -m "新增 XXX（已測試）"

# 6. 完成後刪除備份資料夾
```

---

## 📊 流程圖

```
開始
  ↓
保存混合版本（git commit）
  ↓
複製專案資料夾
  ↓
還原原專案到乾淨版本（git reset --hard HEAD~1）
  ↓
開兩個 VS Code 視窗
  ↓
從混合版本複製一段程式碼到乾淨版本
  ↓
測試
  ├─ 通過 → git commit → 繼續下一段
  └─ 失敗 → 修正 → 重新測試
  ↓
所有程式碼都測試完成？
  ├─ 否 → 回到「複製一段程式碼」
  └─ 是 → 刪除備份資料夾 → 完成
```

---

## 🔧 進階技巧

### 如果想保留混合版本供日後參考

```powershell
# 不要刪除備份資料夾，而是保留在 Git 分支中
cd d:\project\my-aspnet-project-mixed
git branch mixed-version-backup

# 之後如果想查看
git checkout mixed-version-backup
```

### 如果想比對特定檔案

```powershell
# 使用 VS Code 的比對功能
# 在 VS Code 中：
# 1. 打開檔案
# 2. 右鍵 → "Select for Compare"
# 3. 打開另一個檔案
# 4. 右鍵 → "Compare with Selected"
```

---

## 📝 實際案例

### 案例：ASP.NET MVC 加了 3 個 Action

**情況**：
- 加了 `UserList`、`CreateUser`、`DeleteUser` 三個 Action
- 不確定哪些是對的，需要一個一個測試

**操作**：
1. `git commit -m "加了 3 個 Action"`
2. 複製專案到 `my-project-mixed`
3. `git reset --hard HEAD~1`（回到沒有 Action 的狀態）
4. 開兩個 VS Code
5. 從 `my-project-mixed` 複製 `UserList` 到原專案
6. 測試 `UserList` → 通過 → `git commit -m "新增 UserList"`
7. 複製 `CreateUser` → 測試 → 通過 → `git commit`
8. 複製 `DeleteUser` → 測試 → 發現有 bug → 修正 → 測試 → 通過 → `git commit`
9. 刪除 `my-project-mixed` 資料夾

**結果**：
- 原專案有 3 個正確的 Action
- 有 3 個 commit 記錄，每個 Action 一個
- 可以隨時回退到任何一個 Action

---

**最後更新**：2025-12-11
