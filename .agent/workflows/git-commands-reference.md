---
description: Git 常用指令參考 - 完整的 Git 指令清單
---

# 📚 Git 常用指令參考

## 🎯 基本操作

### 初始化和設定

```powershell
# 初始化 Git 倉庫
git init

# 設定使用者資訊
git config --global user.name "你的名字"
git config --global user.email "你的信箱"

# 查看設定
git config --list
```

---

## 📝 日常操作

### 查看狀態

```powershell
# 查看目前狀態
git status

# 查看簡短狀態
git status -s

# 查看提交歷史
git log

# 查看簡短歷史
git log --oneline

# 查看圖形化歷史
git log --oneline --graph --all

# 查看最近 N 個提交
git log --oneline -5
```

### 暫存和提交

```powershell
# 暫存所有改動
git add .

# 暫存特定檔案
git add <檔案名稱>

# 暫存多個檔案
git add file1.txt file2.txt

# 互動式暫存（選擇性暫存）
git add -p

# 提交
git commit -m "提交訊息"

# 修改最後一次提交
git commit --amend -m "新的提交訊息"
```

---

## 🌿 分支操作

### 查看分支

```powershell
# 查看本地分支
git branch

# 查看所有分支（包含遠端）
git branch -a

# 查看分支詳細資訊
git branch -v
git branch -vv  # 包含追蹤資訊
```

### 建立和切換分支

```powershell
# 建立新分支
git branch <分支名稱>

# 切換到分支
git checkout <分支名稱>

# 建立並切換到新分支（推薦）
git checkout -b <分支名稱>

# 新版指令：切換分支
git switch <分支名稱>

# 新版指令：建立並切換
git switch -c <分支名稱>

# 從特定 commit 建立分支
git branch <分支名稱> <commit-id>
git checkout -b <分支名稱> <commit-id>
```

### 合併分支

```powershell
# 合併分支到目前分支
git merge <分支名稱>

# 合併時指定訊息
git merge <分支名稱> -m "合併訊息"

# 取消合併（如果有衝突）
git merge --abort
```

### 刪除分支

```powershell
# 刪除本地分支（已合併）
git branch -d <分支名稱>

# 強制刪除本地分支（未合併）
git branch -D <分支名稱>

# 刪除遠端分支
git push origin --delete <分支名稱>
```

---

## 🔄 遠端操作

### 遠端倉庫管理

```powershell
# 查看遠端倉庫
git remote -v

# 新增遠端倉庫
git remote add origin <URL>

# 修改遠端 URL
git remote set-url origin <新URL>

# 刪除遠端倉庫
git remote remove origin
```

### 推送和拉取

```powershell
# 推送到遠端
git push origin <分支名稱>

# 推送並設定追蹤
git push -u origin <分支名稱>

# 推送所有分支
git push --all origin

# 強制推送（危險！）
git push -f origin <分支名稱>

# 拉取遠端改動
git pull origin <分支名稱>

# 只下載不合併
git fetch origin

# 拉取所有分支
git fetch --all
```

---

## ⏮️ 還原和回退

### 還原檔案

```powershell
# 放棄工作目錄的改動（還沒 add）
git checkout -- <檔案名稱>
git restore <檔案名稱>  # 新版指令

# 放棄所有改動
git checkout -- .
git restore .

# 取消暫存（已 add 但還沒 commit）
git reset HEAD <檔案名稱>
git restore --staged <檔案名稱>  # 新版指令

# 取消所有暫存
git reset HEAD
git restore --staged .
```

### 回退提交

```powershell
# 軟回退（保留改動，取消 commit）
git reset --soft HEAD~1

# 混合回退（保留改動，取消 commit 和 add）
git reset --mixed HEAD~1
git reset HEAD~1  # 預設是 mixed

# 硬回退（完全刪除改動）
git reset --hard HEAD~1

# 回退到特定 commit
git reset --hard <commit-id>

# 回退多個 commit
git reset --hard HEAD~3  # 回退 3 個 commit
```

### 撤銷提交（保留歷史）

```powershell
# 撤銷最後一次提交（建立新的 commit）
git revert HEAD

# 撤銷特定 commit
git revert <commit-id>

# 撤銷多個 commit
git revert HEAD~3..HEAD
```

---

## 💾 暫存改動（Stash）

```powershell
# 暫存目前的改動
git stash

# 暫存並加上說明
git stash save "說明文字"

# 查看暫存列表
git stash list

# 查看暫存內容
git stash show
git stash show -p  # 顯示詳細差異

# 恢復最新的暫存
git stash pop

# 恢復特定暫存
git stash pop stash@{0}

# 恢復但不刪除暫存
git stash apply
git stash apply stash@{0}

# 刪除暫存
git stash drop stash@{0}

# 清空所有暫存
git stash clear
```

---

## 🔍 查看差異

```powershell
# 查看工作目錄的改動（還沒 add）
git diff

# 查看已暫存的改動（已 add 但還沒 commit）
git diff --staged
git diff --cached

# 查看特定檔案的差異
git diff <檔案名稱>

# 比對兩個分支
git diff <分支1> <分支2>

# 比對兩個 commit
git diff <commit1> <commit2>

# 查看特定 commit 的改動
git show <commit-id>
```

---

## 📋 其他實用指令

### 查看檔案歷史

```powershell
# 查看檔案的修改歷史
git log <檔案名稱>

# 查看檔案的每一行是誰修改的
git blame <檔案名稱>

# 查看檔案在特定 commit 的內容
git show <commit-id>:<檔案名稱>
```

### 標籤（Tag）

```powershell
# 查看所有標籤
git tag

# 建立標籤
git tag <標籤名稱>
git tag v1.0.0

# 建立帶說明的標籤
git tag -a v1.0.0 -m "版本 1.0.0"

# 推送標籤到遠端
git push origin <標籤名稱>
git push origin --tags  # 推送所有標籤

# 刪除標籤
git tag -d <標籤名稱>
git push origin --delete <標籤名稱>  # 刪除遠端標籤
```

### 清理

```powershell
# 清理未追蹤的檔案（預覽）
git clean -n

# 清理未追蹤的檔案
git clean -f

# 清理未追蹤的檔案和目錄
git clean -fd

# 清理包含 .gitignore 的檔案
git clean -fdx
```

---

## 🎯 常用組合指令

### 每天上班的流程

```powershell
# 1. 同步遠端
git pull origin main

# 2. 建立新分支開發
git checkout -b feature-new-function

# 3. 開發中...
git add .
git commit -m "完成 XXX 功能"

# 4. 下班前推送
git push origin feature-new-function
```

### 合併分支的流程

```powershell
# 1. 切換到 main
git checkout main

# 2. 更新 main
git pull origin main

# 3. 合併功能分支
git merge feature-new-function

# 4. 推送
git push origin main

# 5. 刪除功能分支
git branch -d feature-new-function
git push origin --delete feature-new-function
```

### 改錯了想回退

```powershell
# 情況 1：還沒 commit
git checkout -- .  # 放棄所有改動

# 情況 2：已經 commit 但還沒 push
git reset --hard HEAD~1  # 回到上一個 commit

# 情況 3：已經 push 了
git revert HEAD  # 建立新的 commit 來撤銷
git push origin main
```

---

## 🚨 緊急情況處理

### 誤刪檔案

```powershell
# 如果還沒 commit
git checkout -- <檔案名稱>

# 如果已經 commit
git log -- <檔案名稱>  # 找到刪除前的 commit
git checkout <commit-id> -- <檔案名稱>
```

### 找回已刪除的 commit

```powershell
# 查看所有操作記錄（包含已刪除的 commit）
git reflog

# 恢復到特定 commit
git reset --hard <commit-id>
```

### 解決合併衝突

```powershell
# 1. 嘗試合併
git merge feature-branch
# 輸出：CONFLICT (content): Merge conflict in file.txt

# 2. 查看衝突的檔案
git status

# 3. 手動編輯衝突的檔案
# 尋找 <<<<<<< HEAD、=======、>>>>>>> 標記
# 手動解決衝突

# 4. 標記為已解決
git add <衝突的檔案>

# 5. 完成合併
git commit -m "解決合併衝突"
```

---

## 💡 最佳實踐

### 提交訊息規範

```powershell
# 好的提交訊息
git commit -m "feat: 新增使用者登入功能"
git commit -m "fix: 修正登入驗證錯誤"
git commit -m "docs: 更新 README 說明"
git commit -m "refactor: 重構使用者服務"

# 提交訊息前綴
# feat: 新功能
# fix: 修復 bug
# docs: 文件更新
# style: 程式碼格式調整
# refactor: 重構
# test: 測試相關
# chore: 雜項（建置、設定等）
```

### 分支命名規範

```powershell
# 功能分支
git checkout -b feature/user-login
git checkout -b feature/payment-integration

# 修復分支
git checkout -b bugfix/login-error
git checkout -b hotfix/security-patch

# 發布分支
git checkout -b release/v1.0.0
```

---

## 🔧 設定別名（Alias）

讓指令更簡短：

```powershell
# 設定別名
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.lg "log --oneline --graph --all"

# 使用別名
git st  # 等於 git status
git co main  # 等於 git checkout main
git lg  # 等於 git log --oneline --graph --all
```

---

## 📚 參考資源

- [Git 官方文件](https://git-scm.com/doc)
- [GitHub 說明](https://docs.github.com/)
- [Git 教學](https://www.atlassian.com/git/tutorials)

---

**最後更新**：2025-12-11
