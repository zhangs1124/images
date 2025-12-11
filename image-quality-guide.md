# 📐 圖片品質與尺寸參考指南

> 適用於 Nano Banana AI 圖片生成
> 
> 最後更新：2025-12-11

---

## 📊 圖片解析度等級

### 標準解析度分類

| 等級 | 解析度 | 像素 | 用途 | Prompt 關鍵詞 |
|------|--------|------|------|--------------|
| **8K** | 7680×4320 | 33.2MP | 專業印刷、大型廣告 | `8K, ultra-high resolution` |
| **4K** | 3840×2160 | 8.3MP | 高品質印刷、專業用途 | `4K, high-resolution` |
| **2K** | 2048×1080 | 2.2MP | 網頁、社交媒體 | `2K, standard resolution` |
| **Full HD** | 1920×1080 | 2.1MP | 一般用途、螢幕顯示 | `Full HD, 1080p` |
| **HD** | 1280×720 | 0.9MP | 網頁預覽 | `HD, 720p` |

---

## 🎯 不同用途的建議解析度

### 電商產品照
```
推薦：4K (3840×2160)
最低：2K (2048×1080)

Prompt 範例：
"Professional product photography, 4K high-resolution, ultra-detailed, 
suitable for e-commerce platform"

專業產品攝影，4K 高解析度，超細節，適合電商平台
```

### 社交媒體

#### Instagram
```
貼文（正方形）：1080×1080
限時動態（直式）：1080×1920
Reels：1080×1920

Prompt 範例：
"Instagram post, square format 1080x1080, high-quality, 
optimized for social media"

Instagram 貼文，正方形格式 1080x1080，高品質，
針對社交媒體優化
```

#### Facebook
```
貼文：1200×630
封面照片：820×312

Prompt 範例：
"Facebook post image, 1200x630, vibrant colors, 
eye-catching design"

Facebook 貼文圖片，1200x630，鮮豔色彩，吸睛設計
```

### 印刷品

#### 海報
```
A4 (210×297mm)：2480×3508 @ 300dpi
A3 (297×420mm)：3508×4961 @ 300dpi
A2 (420×594mm)：4961×7016 @ 300dpi

Prompt 範例：
"Print-ready poster design, 300dpi, CMYK color mode, 
high-resolution 4K, suitable for A3 printing"

印刷就緒海報設計，300dpi，CMYK 色彩模式，
高解析度 4K，適合 A3 印刷
```

#### 名片
```
標準名片：1050×600 @ 300dpi

Prompt 範例：
"Business card design, 300dpi, print-ready, 
high-quality details"

名片設計，300dpi，印刷就緒，高品質細節
```

### 網站使用

#### 網站橫幅
```
桌面版：1920×1080
平板版：1024×768
手機版：750×1334

Prompt 範例：
"Website banner, 1920x1080, responsive design, 
web-optimized quality"

網站橫幅，1920x1080，響應式設計，網頁優化品質
```

#### 部落格特色圖片
```
推薦：1200×630

Prompt 範例：
"Blog featured image, 1200x630, engaging visual, 
optimized for web loading"

部落格特色圖片，1200x630，吸引人的視覺效果，
針對網頁載入優化
```

---

## 🎨 品質相關 Prompt 關鍵詞

### 解析度關鍵詞

#### 超高品質
```
✅ 8K ultra-high resolution
✅ 8K 超高解析度
✅ Ultra-detailed
✅ 超細節
✅ Maximum quality
✅ 最高品質
```

#### 高品質
```
✅ 4K high-resolution
✅ 4K 高解析度
✅ High-quality
✅ 高品質
✅ Professional quality
✅ 專業品質
```

#### 標準品質
```
✅ 2K resolution
✅ 2K 解析度
✅ Standard quality
✅ 標準品質
✅ Full HD
✅ 全高清
```

### 細節程度關鍵詞

```
✅ Ultra-detailed (超細節)
✅ Highly detailed (高度細節)
✅ Intricate details (精緻細節)
✅ Fine details (精細細節)
✅ Sharp focus (銳利對焦)
✅ Crystal clear (清晰透徹)
```

### 專業品質關鍵詞

```
✅ Professional photography (專業攝影)
✅ Studio quality (工作室品質)
✅ Commercial grade (商業級)
✅ Print-ready (印刷就緒)
✅ Photorealistic (照片般真實)
✅ Cinema quality (電影品質)
```

---

## 📐 寫實比例（Aspect Ratio）

### 常用比例

| 比例 | 尺寸範例 | 用途 | Prompt |
|------|---------|------|--------|
| **1:1** | 1080×1080 | Instagram 貼文 | `square format, 1:1 aspect ratio` |
| **4:3** | 1600×1200 | 傳統照片 | `4:3 aspect ratio, traditional photo` |
| **16:9** | 1920×1080 | 影片、橫幅 | `16:9 widescreen, cinematic` |
| **9:16** | 1080×1920 | 限時動態、Reels | `9:16 vertical, mobile-optimized` |
| **3:2** | 1800×1200 | 專業攝影 | `3:2 aspect ratio, DSLR standard` |
| **21:9** | 2560×1080 | 超寬螢幕 | `21:9 ultrawide, panoramic` |

---

## 💡 完整 Prompt 範例

### 範例 1：電商產品照（最高品質）

```
Professional product photography of [product name]. 
Pure white background, 45-degree angle view. 
8K ultra-high resolution, maximum quality, ultra-detailed. 
Sharp focus, crystal clear details, photorealistic rendering. 
Studio lighting, commercial grade quality, print-ready. 
Suitable for e-commerce platform and professional catalog.

【產品名稱】的專業產品攝影。
純白背景，45度角視角。
8K 超高解析度，最高品質，超細節。
銳利對焦，清晰透徹細節，照片般真實渲染。
工作室照明，商業級品質，印刷就緒。
適合電商平台和專業目錄。
```

### 範例 2：Instagram 貼文（社交媒體優化）

```
Instagram-worthy image of [subject]. 
Square format 1080x1080, optimized for social media. 
High-quality, vibrant colors, eye-catching composition. 
Sharp details, professional photography style. 
Suitable for Instagram feed, engaging visual.

適合 Instagram 的【主題】圖片。
正方形格式 1080x1080，針對社交媒體優化。
高品質，鮮豔色彩，吸睛構圖。
銳利細節，專業攝影風格。
適合 Instagram 動態，吸引人的視覺效果。
```

### 範例 3：印刷海報（印刷品質）

```
Print-ready poster design for [topic]. 
A3 size (297×420mm), 300dpi resolution. 
4K high-resolution, ultra-detailed, sharp and clear. 
CMYK color mode, professional print quality. 
Suitable for large format printing, commercial use.

【主題】的印刷就緒海報設計。
A3 尺寸 (297×420mm)，300dpi 解析度。
4K 高解析度，超細節，銳利清晰。
CMYK 色彩模式，專業印刷品質。
適合大型印刷，商業用途。
```

### 範例 4：網站橫幅（網頁優化）

```
Website banner image for [purpose]. 
1920x1080 resolution, 16:9 widescreen format. 
High-quality, web-optimized, fast loading. 
Responsive design, suitable for desktop and tablet. 
Professional web design quality.

【用途】的網站橫幅圖片。
1920x1080 解析度，16:9 寬螢幕格式。
高品質，網頁優化，快速載入。
響應式設計，適合桌面和平板。
專業網頁設計品質。
```

---

## 🎯 品質選擇建議

### 何時使用 8K

✅ **適合**：
- 大型印刷品（海報、廣告看板）
- 專業攝影作品
- 需要極致細節的產品照
- 高端商業用途

⚠️ **注意**：
- 檔案大小非常大
- 生成時間較長
- 可能超出某些平台限制

### 何時使用 4K

✅ **適合**：
- 電商產品照
- 專業網站
- 中型印刷品（A4-A3）
- 高品質社交媒體內容

💡 **推薦**：最常用的專業品質

### 何時使用 2K/Full HD

✅ **適合**：
- 社交媒體貼文
- 網站內容
- 部落格圖片
- 一般用途

💡 **推薦**：網頁使用的最佳平衡

---

## 📝 快速參考表

### 依用途選擇

| 用途 | 建議解析度 | 建議比例 | 品質關鍵詞 |
|------|-----------|---------|-----------|
| 電商產品 | 4K | 1:1 或 4:3 | `4K, ultra-detailed, professional` |
| Instagram | 1080×1080 | 1:1 | `high-quality, social media optimized` |
| Facebook | 1200×630 | ~2:1 | `vibrant, eye-catching` |
| 印刷海報 | 4K-8K | 依尺寸 | `300dpi, print-ready, CMYK` |
| 網站橫幅 | 1920×1080 | 16:9 | `web-optimized, responsive` |
| 部落格 | 1200×630 | ~2:1 | `web-friendly, engaging` |
| 限時動態 | 1080×1920 | 9:16 | `vertical, mobile-optimized` |

---

## 🔧 Prompt 組合公式

### 基本公式

```
[主體描述] + [場景] + [風格] + [品質設定] + [用途]
```

### 品質設定範例

**最高品質**：
```
8K ultra-high resolution, maximum quality, ultra-detailed, 
crystal clear, photorealistic, professional grade
```

**高品質**：
```
4K high-resolution, high-quality, detailed, 
sharp focus, professional photography
```

**標準品質**：
```
2K resolution, good quality, clear details, 
suitable for web use
```

---

## 💡 實用技巧

### 1. 根據最終用途選擇

```
印刷 → 4K-8K + 300dpi
網頁 → 2K-4K
社交媒體 → Full HD - 2K
```

### 2. 平衡品質與檔案大小

```
高品質 = 大檔案 = 慢載入
適當品質 = 合理檔案 = 快載入
```

### 3. 組合使用關鍵詞

```
不要只說 "4K"
要說 "4K high-resolution, ultra-detailed, professional quality"
```

---

**最後更新**：2025-12-11
**版本**：v1.0
