# 🎨 Nano Banana AI 圖形 Prompt 提示詞集合

> 來源：
> - [Fotor - Nano Banana Model Prompts](https://www.fotor.com/tw/blog/nano-banana-model-prompts/)
> - [iBest - Nano Banana 教學](https://www.ibest.com.tw/news-detail/nano-banana-ai/)
> - [Master Concept - 產業專屬 Prompts](https://masterconcept.ai/zh-hant/learning-column/google-cloud-zh-hant/google-ais-nano-banana-unlocked-steal-these-prompts-for-your-industry/)
> 
> 最後更新：2025-12-11

---

## 🤖 什麼是 Nano Banana？

**Nano Banana** (正式名稱：**Gemini 2.5 Flash Image**) 是 Google 最新推出的原生多模態 AI 模型，專門用於圖片生成和編輯。

### 核心特色

| 特色 | 說明 |
|------|------|
| **對話式編輯** | 用口語化的方式修改圖片，不需要複雜的提示詞 |
| **多圖合成** | 同時理解多張圖片，進行合成或比較 |
| **深層邏輯推理** | 真正「看懂」圖片細節與邏輯關係 |
| **精準文字渲染** | 生成清晰的文字（目前英文較準確） |

---

## 🎯 Nano Banana 可以做什麼？

### 1. 強大的生成能力

- **文字轉圖片**：用簡單或複雜的文字描述生成高品質圖片
- **文字渲染**：在圖片中精準生成清晰的文字內容
- **風格多樣**：支援寫實、動漫、3D、插畫等多種風格

### 2. 革命性的互動編輯

#### 對話式編輯 (Conversational Editing)
```
範例：
生成一張貓咪圖後，直接說：
「幫牠戴上一頂紅色帽子」
「讓背景的天空更藍一些」
```

#### 圖像+文字編輯
```
範例：
上傳一張產品圖並指示：
「把這個瓶子的顏色換成霧面黑」
```

#### 多圖融合 / 風格轉換
```
範例：
「將 A 圖的風格套用到 B 圖」
「將這兩張圖片的元素無縫拼接」
```

#### 逐步優化
```
持續對話微調圖片，直到滿意為止
```

### 3. 多圖合成與推理 (Multi-Image Composition & Reasoning)

```
範例：
給它兩張設計圖，並問：
「請將 A 圖的 logo 放到 B 圖的產品上」
```

### 4. 深層邏輯推理 (Deep Logical Reasoning)

```
範例：
上傳一張流程圖，並問：
「哪個步驟可能出錯？」
```

---

## 🌐 哪裡可以使用 Nano Banana？

### 官方平台

| 平台 | 連結 | 說明 |
|------|------|------|
| **Google AI Studio** | [aistudio.google.com](http://aistudio.google.com/prompts/new_chat?model=gemini-2.5-flash-image-preview) | 專業開發者平台 |
| **Gemini 圖像生成** | [gemini.google.com](https://gemini.google.com/app?hl=zh-TW) | 一般使用者介面 |
| **Fotor AI** | [fotor.com](https://www.fotor.com/images/create/) | 整合 Nano Banana 的線上工具 |

---

## 📋 目錄

- [什麼是 Nano Banana](#什麼是-nano-banana)
- [Nano Banana 可以做什麼](#nano-banana-可以做什麼)
- [哪裡可以使用 Nano Banana](#哪裡可以使用-nano-banana)
- [影像效果](#影像效果)
- [圖片編輯](#圖片編輯)
- [產業專屬 Prompt](#產業專屬-prompt)
- [使用技巧](#使用技巧)
- [進階 Prompt 技巧](#進階-prompt-技巧)

---

## 影像效果

### 1. 3D 手辦

**中文提示詞：**
```
將上傳圖片中的人物轉換為 1/7 商業化比例全身模型，以真實風格和真實環境呈現。將模型放置在電腦桌上，使用透明圓形壓克力基座（不含任何文字）。電腦螢幕上顯示該模型的 ZBrush（數位雕刻軟體） 建模過程。在電腦螢幕旁邊，放置一個 BANDAI（萬代） 風格的玩具包裝盒，盒面上印有原始插畫作品。
```

**English Prompt:**
```
Turn the person in the uploaded picture into a 1/7 scale commercialized figure of the character in the illustration, in a realistic style and environment. Place the figure on a computer desk, using a circular transparent acrylic base without any text. On the computer screen, display the ZBrush modeling process of the figure. Next to the computer screen, place a BANDAI-style toy packaging box printed with the original artwork.
```

---

### 2. Q版毛線娃娃

**中文提示詞：**
```
一張特寫的專業構圖照片，展示一個手工鉤織的毛線娃娃被兩隻手輕輕捧著。娃娃呈圓潤造型，具有可愛的 Q 版形象，來源於【上傳的圖片】角色，色彩鮮明對比強烈，細節豐富。捧著娃娃的雙手自然溫柔，手指姿態清晰可見，皮膚紋理和光影過渡自然，傳達出溫暖且真實的觸感。背景略微模糊，描繪室內環境，有溫暖的木質桌面，窗戶透入自然光線，營造舒適且親密的氛圍。整體影像傳達出精緻工藝與珍愛溫度的感覺。
```

**English Prompt:**
```
A close-up, professionally composed photograph showcasing a hand-crocheted yarn doll gently cradled by two hands. The doll has a rounded shape, featuring the cute chibi image of the [upload image] character, with vivid contrasting colors and rich details. The hands holding the doll are natural and gentle, with clearly visible finger postures, and natural skin texture and light/shadow transitions, conveying a warm and realistic touch. The background is slightly blurred, depicting an indoor environment with a warm wooden tabletop and natural light streaming in from a window, creating a comfortable and intimate atmosphere. The overall image conveys a sense of exquisite craftsmanship and cherished warmth.
```

---

### 3. 透明扭蛋膠囊手辦

**中文提示詞：**
```
将上传图片中的人物，转换为一個細節精緻的透明扭蛋膠囊場景模型，被手指捏持著。膠囊內部：【姿勢】【模型外觀、服裝與配件的簡短描述】，背景元素如【相關場景：運動場、舞台、講堂等】。光線應該具有戲劇性和電影感，與角色主題相符。膠囊上蓋為透明，底座為彩色【選擇適合的顏色：如皇家藍、金色、黑色、紅色】，裝飾有【與角色相關的圖案元素】。底座標示【姓名或暱稱】，字體樣式與整體風格相符。整體設計應呈現迷你收藏品感，具有寫實細節、柔和散景效果，並以 1080x1080 方形構圖呈現。
```

**English Prompt:**
```
Turn the person in the uploaded picture into a detailed transparent gashapon capsule diorama, held between fingers. Inside: [pose, short description of figure's look, clothing, and accessories], with background elements such as [relevant setting: stadium, stage, lecture hall, etc.]. Lighting should be dramatic and cinematic, matching their theme. The capsule has a transparent top and a colored base [choose fitting color: e.g., royal blue, gold, black, red], decorated with [motifs related to the person]. The base is labeled with [NAME or NICKNAME] in a matching font style. The design should look like a miniature collectible, with photorealistic detail, soft bokeh, and a square 1080x1080 composition.
```

**注意：** 請替換 [ ] 中的內容為具體描述

---

### 4. 角色毛絨玩偶

**中文提示詞：**
```
將上傳圖片中的人物變為一個柔軟、高品質的絨毛玩偶，擁有誇大的頭部、小巧的身體，以及短胖的四肢。材質為毛絨布料，可見縫線並有刺繡的臉部特徵。玩偶呈坐姿或站姿，背景為中性背景。表情可愛或富有表情，如果有相關，穿著簡單服裝或經典配件。光線柔和均勻，呈現真實、可收藏的絨毛玩偶質感。置中全身視角。1080x1080。
```

**English Prompt:**
```
Turn the person in the uploaded picture into a soft, high-quality plush toy, with an oversized head, small body, and stubby limbs. Made of fuzzy fabric with visible stitching and embroidered facial features. The plush is shown sitting or standing against a neutral background. The expression is cute or expressive, and it wars simple clothes or iconic accessories if relevant. Lighting is soft and even, with a realistic, collectible plush look. Centered, full-body view. 1080x1080.
```

---

### 5. iPhone 自拍

**中文提示詞：**
```
將上傳圖片轉換為一張普通的 iPhone 自拍照，沒有明確主體或構圖感——就像隨意拍攝的隨手快照。照片應帶有輕微的動態模糊，光線不均勻，由陽光或室內燈光造成輕微過曝。角度尷尬，構圖凌亂，整體美感刻意平淡——就像不小心從口袋拿出手機時拍到的一樣。拍攝時間為夜晚，地點在【地點】旁。
```

**English Prompt:**
```
Turn the uploaded picture into an extremely ordinary and unremarkable iPhone selfie, with no clear subject or sense of composition — just like a random snapshot taken casually. The photo should include slight motion blur, with uneven lighting caused by sunlight or indoor lights resulting in mild overexposure. The angle is awkward, the composition is messy, and the overall aesthetic is deliberately plain — as if it was accidentally taken while pulling the phone out of a pocket. The subjects taken at night, next to the [Location].
```

---

### 6. Q版表情貼紙

**中文提示詞：**
```
做出俏皮的雙手比出勝利手勢並眨眼。眼中帶淚，嘴唇微微顫動，呈現可愛哭泣表情。雙臂張開，做出溫暖、熱情的擁抱姿勢。側躺睡覺，頭枕小枕頭，帶著甜美微笑。自信地指向前方，周圍環繞著閃亮視覺效果。飛吻，周圍漂浮心形符號。保持 Q 版風格。誇張、表情豐富的大眼睛。柔和的臉部線條。背景：鮮豔紅色，搭配星星或彩色紙屑元素裝飾。每個貼圖周圍保留一些乾淨的白色空間。長寬比：9:16。
```

**English Prompt:**
```
Making a playful peace sign with both hands and winking. Tearful eyes and slightly trembling lips, showing a cute crying expression. Arms wide open in a warm, enthusiastic hug pose. Lying on their side asleep, resting on a tiny pillow with a sweet smile. Pointing forward with confidence, surrounded by shining visual effects. Blowing a kiss, with heart symbols floating around. Maintain the chibi aesthetic. Exaggerated, expressive big eyes. Soft facial lines. Background: Vibrant red with star or colorful confetti elements for decoration. Leave some clean white space around each sticker. Aspect ratio: 9:16
```

---

### 7. Funko Pop 手辦

**中文提示詞：**
```
將照片中的人物轉換為 Funko Pop（Funko 手辦）風格盒裝呈現，以等角視圖（isometric view）展示。包裝上標註標題：【名字】。盒內呈現以照片人物為原型的 Q 版（chibi）公仔，以及其重要配件：手槍、手錶、西裝和其他標誌性物品。盒子旁展示實體公仔的寫實渲染效果，細節與光影豐富，呈現如真實產品般的質感。
```

**English Prompt:**
```
Create a detailed 3D render of a chibi Funko Pop figure, strictly based on the provided reference photo. The figure should accurately reflect the person's appearance, hairstyle, attire, and characteristic style from the photo. High detail, studio lighting, photorealistic texture, pure white background.
```

---

### 8. 吉卜力風格

**中文提示詞：**
```
將這張照片重繪為吉卜力（Ghibli）風格。
```

**English Prompt:**
```
Redraw this photo in Ghibli style
```

---

### 9. 遊戲 UI

**中文提示詞：**
```
一張充滿活力的節奏舞蹈遊戲截圖，呈現三個來自參考照片的相同 3D 動畫角色，保留她獨特髮型、耳機、太陽眼鏡、運動風黃色褲子以及自信的舞蹈姿勢。沉浸式電影光影效果，霓虹粉紅與紫色光暈，光亮反射的舞蹈地板在聚光燈下閃耀，動態 3D 卡通風格。節奏遊戲界面包含沉浸式 UI：頂部分數計量表、與節拍同步的彩色音樂波形動畫、舞台倒數計時器，以及漂浮的連擊數字。高度細節化，遊戲氛圍濃厚，帶有能量條、霓虹粒子效果，以及沉浸式街機節奏遊戲 HUD 元素。超細緻、電影感、沉浸式、3D 動畫效果。
```

**English Prompt:**
```
A vibrant rhythm dance game screenshot featuring three same 3D animated characters from the reference photo, keeping her unique hairstyle, headphones, sunglasses, sporty yellow pants, and confident dance pose. Immersive cinematic lighting with neon pink and purple glow, glossy reflective dance floor shining under spotlights, dynamic 3D cartoon style. Rhythm game interface with immersive UI: score meter at the top, colorful music waveform animations synced to the beat, stage timer countdown, and floating combo numbers. Highly detailed, game-like atmosphere with energy bars, neon particle effects, and immersive arcade rhythm game HUD elements. Ultra-detailed, cinematic, immersive, 3D animation.
```

---

### 10. 多張圖片融合

**English Prompt:**
```
Combine multiple images ([Image1], [Image2], [Image3], …) into a single cohesive image. Keep all key subjects recognizable and maintain their proportions and details. Blend the images naturally with consistent lighting, shadows, perspective, and style. Photorealistic, high-resolution, seamless integration.
```

---

### 11. 風格融合

**English Prompt:**
```
Transform this image [Image1] into the artistic style of [Image2]. Keep the main subject, composition, and details from [Image1], but apply the colors, textures, and overall aesthetic of [Image2]. High-quality, [illustration] style, consistent details.
```

**注意：** 將 [illustration] 替換為具體風格描述

---

### 12. 虛擬換裝

**English Prompt:**
```
Keep the character in [Image1] unchanged, but replace her pant with the outfit in [Image2]. Maintain the same pose, body proportions, and facial features, while applying the color, texture, and style of the pants in [Image2]. High-quality, realistic, consistent detail.
```

---

## 圖片編輯

### 13. 換表情

**English Prompt:**
```
Keep the person from [Image1] unchanged, but change their facial expression to [desired expression, e.g., smiling, surprised, angry]. Preserve the pose, body proportions, hairstyle, and overall appearance. Maintain realistic lighting, shadows, and photorealistic details.
```

---

### 14. 換姿勢

**English Prompt:**
```
Take the two men and place them in the exact poses of the man in green carrying the man in red. Preserve their identities, body proportions, and clothing details. Ensure the pose is natural and realistic, with consistent lighting, shadows, and perspective. Photorealistic, high-resolution result.
```

---

### 15. 改變身材

**English Prompt:**
```
Reshape the body of the person in [Image1] into a [target body type]. Keep the face, identity, hairstyle, and clothing consistent. Ensure realistic anatomy, natural proportions, and photorealistic details.
```

---

### 16. 九宮格肖像

**English Prompt:**
```
Using the uploaded photo as a reference, generate a set of 9 vibrant half-length portraits featuring natural life. Each portrait should show a different pose and be placed in a unique setting, with rich, colorful details that highlight the diversity of nature.
```

---

### 17. 修改背景

**English Prompt:**
```
Replace the background of [Image1] with [desired background description, e.g., a beach, a forest, a city skyline]. Keep the main subject (person/object) unchanged, maintaining original proportions, lighting, and details. Ensure the subject blends naturally with the new environment. Photorealistic, high-resolution, seamless integration.
```

---

### 18. 添加或移除物品

**添加物品：**
```
Add [desired element, e.g., a tree, a lamp, a dog] to [Image1]. Place it naturally in the scene, matching the lighting, perspective, and style. Keep the original elements unchanged. Photorealistic, seamless integration.
```

**移除物品：**
```
Remove [element to remove, e.g., a person, a car, a sign] from [Image1]. Fill the background naturally to maintain the scene's continuity, lighting, and details. Keep all other elements unchanged. Photorealistic, high-resolution.
```

---

### 19. 改變鏡頭角度

**English Prompt:**
```
Recreate the person from [Image1] in four different camera perspectives. Keep the subject's identity, body proportions, and clothing consistent across all four images. Maintain the same background environment as [Image1], with photorealistic lighting, natural shadows, and high-quality details. Generate four variations side by side:
1. Bird's-eye view (from above).
2. Rear view (from behind).
3. Side profile view.
4. Close-up portrait view.
```

---

### 20. 編輯圖中文字

**English Prompt:**
```
Edit the text in [Image1]. Replace the existing text with "[your new text]" while keeping the background, design, and other elements unchanged. Match the font style, size, and color to look natural and consistent with the image. Photorealistic, seamless integration.
```

---

### 21. 生成隨時間自然變化的圖片

**English Prompt:**
```
Generate an image of the same scene as [Image1], but showing how it looks 10 minutes later. Keep the environment and style consistent, but add natural changes over time such as light, weather, people and so on. Photorealistic, seamless continuity.
```

---

### 22. 提取物品

**English Prompt:**
```
Extract the clothing from [Image1] and present it as a clean e-commerce product photo. Remove the model's body completely. Keep the outfit in natural 3D shape, with realistic fabric folds, seams, and textures. Display the garment as if photographed on a mannequin or neatly laid flat, centered on a pure white or transparent background. High-resolution, professional lighting, suitable for online fashion catalog.
```

---

### 23. 修復畫質

**English Prompt:**
```
Enhance [Image1] to improve overall quality and detail. Keep the original composition, colors, and style intact. Increase resolution, sharpness, texture clarity, and lighting realism. Output as a photorealistic, high-resolution image.
```

---

### 24. 修改天氣

**English Prompt:**
```
Change the weather in [Image1] to [desired weather, e.g., rainy, snowy, foggy, sunny]. Keep the main subject and overall scene intact. Adjust lighting, shadows, colors, and environmental effects to match the new weather. Photorealistic, seamless integration, high-resolution.
```

---

### 25. 修改圖片顏色

**English Prompt:**
```
Change the colors in [Image1] to [desired color/style, e.g., warm tones, cool blue tones, pastel colors]. Keep the main subject and composition intact. Adjust lighting, shadows, and overall color balance to match the new color scheme. Photorealistic, high-resolution, natural-looking result.
```

---

### 26. 替換物品

**English Prompt:**
```
Replace [target element or area] in [Image1] with [new element or reference, e.g., a different person, object, or scene]. Keep all other parts of the image unchanged. Ensure the replacement blends naturally with lighting, perspective, and overall style. Photorealistic, high-resolution, seamless integration.
```

---

### 27. 圖片延伸

**English Prompt:**
```
Extend [Image1] beyond its original borders using outpainting. Keep the main subject and composition intact. Generate new content around the edges that matches the style, colors, lighting, and perspective of the original image. Photorealistic, high-resolution, seamless integration.
```

---

### 28. 線稿變彩圖

**English Prompt:**
```
Convert the line art in [Image1] into a fully colored and detailed image. Preserve all original outlines and compositions. Apply [desired style, e.g., photorealistic, anime, cartoon, digital painting] with realistic lighting, shadows, and textures. High-resolution, natural, seamless rendering.
```

---

### 29. 3x3 九宮格照片

**English Prompt:**
```
Turn the photo into a 3x3 grid of photo strips with different studio-style poses and expressions.
```

---

### 30. AI 室內設計

**English Prompt:**
```
Step one: Add a comfortable gray sofa and a wooden coffee table in the center, matching the room's contemporary style, photorealistic render.

Step two: Add more furniture-like items to the foreground and more daily necessities on the table. Also, change the wallpaper to something warmer.
```

---

### 31. 食材變料理

**English Prompt:**
```
Here are the items available: [List of items]. Based on these items, create an image of a [type of object/scene] that can be made or represented by combining them. The composition should make logical sense, considering the relationship between the items. Ensure the image is [visual style]. It should be with appropriate proportions and clear placement of each item.
```

**注意：** 替換 [List of items], [type of object/scene], [visual style] 為具體描述

---

## 🏢 產業專屬 Prompt

### 電商 / E-Commerce

#### 產品去背
```
Remove the background from this product image and replace it with a pure white background. Keep the product details, shadows, and reflections natural. Professional e-commerce style, high-resolution.

將此產品圖片去背，替換為純白色背景。保持產品細節、陰影和反射自然。專業電商風格，高解析度。
```

#### 產品情境圖
```
Place this product in a [lifestyle setting, e.g., modern living room, outdoor cafe]. The product should be the focal point, with natural lighting and realistic shadows. Photorealistic, high-quality, suitable for e-commerce.

將此產品放置在【生活場景，例如：現代客廳、戶外咖啡廳】中。產品應為焦點，具有自然光線和真實陰影。寫實風格，高品質，適合電商使用。
```

#### 多角度展示
```
Generate 4 different angles of this product: front view, side view, top view, and 45-degree angle. Maintain consistent lighting and background. Professional product photography style.

生成此產品的 4 個不同角度：正面、側面、俯視和 45 度角。保持一致的光線和背景。專業產品攝影風格。
```

---

### 餐飲 / Food & Beverage

#### 菜單美食攝影
```
Transform this food photo into a professional menu-style image. Enhance colors to make the food look fresh and appetizing. Add soft natural lighting from the side. Clean background, high-resolution, suitable for restaurant menu.

將此美食照片轉換為專業菜單風格圖片。增強色彩使食物看起來新鮮誘人。添加柔和的側面自然光。乾淨背景，高解析度，適合餐廳菜單。
```

#### 食材到料理
```
Based on these ingredients [list ingredients], create a beautifully plated dish. Professional food styling, garnished appropriately, natural lighting, shallow depth of field, restaurant-quality presentation.

根據這些食材【列出食材】，創造一道精美擺盤的料理。專業食物造型，適當裝飾，自然光線，淺景深，餐廳級呈現。
```

#### 飲品視覺化
```
Create a refreshing beverage photo with [drink description]. Include condensation on the glass, ice cubes, garnish with [mint/lemon/berries]. Bright, clean background, professional beverage photography style.

創造一張清爽的飲品照片，包含【飲品描述】。玻璃杯上有水珠，冰塊，用【薄荷/檸檬/莓果】裝飾。明亮乾淨背景，專業飲品攝影風格。
```

---

### 教育 / Education

#### 教學圖表
```
Convert this concept into an educational infographic. Use clear icons, simple illustrations, and a logical flow. Color-coded sections, easy to understand, suitable for [age group/education level].

將此概念轉換為教育資訊圖表。使用清晰圖標、簡單插圖和邏輯流程。色彩編碼區塊，易於理解，適合【年齡層/教育程度】。
```

#### 課程封面
```
Design a course cover image for [course topic]. Modern, professional style with relevant imagery. Include space for text overlay. Vibrant colors, engaging design, suitable for online learning platform.

為【課程主題】設計課程封面圖片。現代專業風格，相關圖像。包含文字覆蓋空間。鮮豔色彩，吸引人的設計，適合線上學習平台。
```

#### 互動式學習素材
```
Create a set of 6 educational flashcards about [topic]. Each card should have a clear illustration, simple design, and space for text. Colorful, child-friendly style, consistent design across all cards.

創造一組 6 張關於【主題】的教育閃卡。每張卡片應有清晰插圖、簡單設計和文字空間。色彩豐富，兒童友善風格，所有卡片設計一致。
```

---

### 房地產 / Real Estate

#### 空間視覺化
```
Transform this empty room into a [furnished living room/bedroom/office]. Add appropriate furniture, decor, and lighting. Modern style, warm atmosphere, photorealistic rendering, suitable for property listing.

將此空房間轉換為【已佈置的客廳/臥室/辦公室】。添加適當家具、裝飾和照明。現代風格，溫暖氛圍，寫實渲染，適合房產列表。
```

#### 建築外觀優化
```
Enhance this property exterior photo. Improve lighting, add blue sky, green lawn, and landscaping. Remove any distractions. Professional real estate photography style, high-resolution.

增強此房產外觀照片。改善光線，添加藍天、綠色草坪和景觀。移除任何干擾物。專業房地產攝影風格，高解析度。
```

#### 虛擬裝潢
```
Apply [modern/minimalist/industrial] interior design style to this space. Change wall colors, flooring, and add appropriate furniture and decor. Maintain the room's dimensions and structure. Photorealistic, professional interior design visualization.

將【現代/極簡/工業】室內設計風格應用到此空間。更改牆壁顏色、地板，添加適當家具和裝飾。保持房間尺寸和結構。寫實，專業室內設計視覺化。
```

---

### 時尚 / Fashion

#### 服裝展示
```
Display this clothing item on a [mannequin/model] in a professional fashion photography style. Studio lighting, clean background, show fabric texture and details clearly. High-fashion, editorial quality.

將此服裝展示在【人體模型/模特】上，專業時尚攝影風格。工作室照明，乾淨背景，清楚展示布料質感和細節。高級時尚，編輯品質。
```

#### 穿搭組合
```
Create a complete outfit using this [item]. Add complementary clothing pieces, accessories, and shoes. Modern, stylish look, suitable for [occasion]. Flat lay or styled on model, fashion editorial style.

使用此【單品】創造完整穿搭。添加互補的服裝單品、配件和鞋子。現代時尚外觀，適合【場合】。平鋪或模特穿著，時尚編輯風格。
```

#### 色彩變化
```
Show this garment in 5 different color variations: [list colors]. Maintain the same style, fit, and fabric texture. Display in a grid layout, professional product photography, consistent lighting.

展示此服裝的 5 種不同顏色變化：【列出顏色】。保持相同款式、版型和布料質感。網格佈局展示，專業產品攝影，一致照明。
```

---

### 醫療 / Healthcare

#### 醫療說明圖
```
Create a medical illustration explaining [medical concept/procedure]. Use clear, simple visuals with anatomical accuracy. Professional medical illustration style, appropriate for patient education materials.

創造醫療插圖解釋【醫療概念/程序】。使用清晰簡單的視覺效果，解剖學準確。專業醫療插圖風格，適合患者教育材料。
```

#### 健康資訊圖表
```
Design an infographic about [health topic]. Include statistics, icons, and easy-to-understand visuals. Clean, professional design, suitable for healthcare website or brochure.

設計關於【健康主題】的資訊圖表。包含統計數據、圖標和易於理解的視覺效果。乾淨專業設計，適合醫療網站或手冊。
```

---

### 科技 / Technology

#### 產品 UI 展示
```
Create a mockup of this app/software interface on [device type]. Show the UI in use with realistic screen content. Professional tech product photography, clean background, high-resolution.

在【設備類型】上創造此應用程式/軟體介面的模型。展示使用中的 UI 和真實螢幕內容。專業科技產品攝影，乾淨背景，高解析度。
```

#### 技術流程圖
```
Visualize this technical process as a flowchart. Use modern design, clear icons, and logical flow. Color-coded steps, professional tech documentation style.

將此技術流程視覺化為流程圖。使用現代設計、清晰圖標和邏輯流程。色彩編碼步驟，專業技術文件風格。
```

---

### 旅遊 / Travel

#### 景點視覺化
```
Enhance this travel destination photo. Improve colors, lighting, and atmosphere. Add blue sky, vibrant colors, and remove tourists or distractions. Professional travel photography style, inspiring and attractive.

增強此旅遊目的地照片。改善色彩、光線和氛圍。添加藍天、鮮豔色彩，移除遊客或干擾物。專業旅遊攝影風格，鼓舞人心且吸引人。
```

#### 行程視覺化
```
Create a visual itinerary for a [duration] trip to [destination]. Include iconic landmarks, activities, and local experiences. Map-style layout with photos and icons, modern travel guide design.

為【目的地】的【時長】旅行創造視覺行程。包含標誌性地標、活動和當地體驗。地圖風格佈局，附照片和圖標，現代旅遊指南設計。
```

---

### 社交媒體 / Social Media

#### Instagram 貼文
```
Create an Instagram-worthy image for [topic/product]. Trendy, eye-catching design with vibrant colors. Include space for text overlay. Square format (1080x1080), modern social media aesthetic.

為【主題/產品】創造適合 Instagram 的圖片。時尚吸睛設計，鮮豔色彩。包含文字覆蓋空間。正方形格式 (1080x1080)，現代社交媒體美學。
```

#### 故事 / 限時動態
```
Design a story template for [brand/topic]. Vertical format (1080x1920), modern design with space for text and stickers. Engaging, on-brand aesthetic.

為【品牌/主題】設計限時動態模板。垂直格式 (1080x1920)，現代設計，包含文字和貼紙空間。吸引人，符合品牌美學。
```

---

## 使用技巧

### 💡 提供詳細的描述
- 越詳細的描述，AI 生成的結果越精確
- 包含具體的顏色、材質、光線等細節

### 💡 逐步細化
- 先生成基本版本
- 再根據結果逐步調整和優化

### 💡 指定藝術風格
- 明確指定想要的風格（寫實、動漫、卡通等）
- 可以參考特定藝術家或作品風格

### 💡 提供常見信息
- 包含場景、時間、天氣等背景資訊
- 有助於 AI 理解整體氛圍

### 💡 嘗試多樣變化
- 同一個 prompt 可以生成多次
- 比較不同結果，選擇最佳版本

### 💡 注意光影效果一致
- 確保光源方向和強度合理
- 陰影和高光要符合物理規律

---

## 🚀 進階 Prompt 技巧

### 1. JSON 格式 Prompt

使用結構化的 JSON 格式可以更精確地控制生成結果：

#### 人物場景 JSON 模板

```json
{
  "subject": {
    "type": "描述主體類型",
    "pose": "姿勢描述",
    "expression": "表情描述"
  },
  "appearance": {
    "hair_color": "髮色",
    "hair_style": "髮型",
    "complexion": "膚色"
  },
  "clothing": {
    "top": "上衣描述",
    "bottom": "下身描述",
    "accessories": "配件"
  },
  "environment": {
    "setting": "場景設定",
    "details": "環境細節"
  },
  "lighting": {
    "type": "光線類型",
    "mood": "氛圍"
  },
  "camera": {
    "angle": "拍攝角度",
    "lens_effect": "鏡頭效果",
    "framing": "構圖"
  },
  "style": {
    "overall": "整體風格"
  }
}
```

#### 實際範例：聖誕市集自拍

```json
{
  "subject": {
    "type": "beautiful young woman (early 20s)",
    "pose": "sitting on a wooden market bench with knees pulled up",
    "expression": "cute, warm, festive, giving a cheerful wink"
  },
  "appearance": {
    "hair_color": "dark brown",
    "hair_style": "long loose waves with a cozy knit headband",
    "complexion": "fair with rosy winter cheeks"
  },
  "clothing": {
    "top": "cream knit sweater",
    "bottom": "red corduroy shorts",
    "socks": "white wool socks",
    "shoes": "tan winter boots with faux fur"
  },
  "environment": {
    "setting": "outdoor Christmas market",
    "details": "twinkle lights, wooden stalls, warm hanging lanterns"
  },
  "lighting": {
    "type": "warm golden fairy-light glow",
    "mood": "cozy, festive, romantic"
  },
  "camera": {
    "angle": "low-to-mid angle",
    "lens_effect": "slight wide-angle with warm bloom",
    "framing": "subject centered among Christmas lights"
  },
  "style": {
    "overall": "Christmas market photography with warm festive atmosphere"
  }
}
```

---

### 2. 電影分鏡 (Contact Sheet) 技巧

創造 3x3 電影故事板網格，展示同一主體的 9 個不同鏡頭：

#### 分鏡結構

```
第 1 行（建立背景）：
1. 大遠景 (ELS)：主體在廣闊環境中
2. 全景 (LS)：完整主體從頭到腳
3. 中遠景：從膝蓋以上

第 2 行（核心覆蓋）：
4. 中景 (MS)：從腰部以上
5. 中特寫 (MCU)：從胸部以上
6. 特寫 (CU)：臉部特寫

第 3 行（細節與角度）：
7. 大特寫 (ECU)：微距細節（眼睛、手）
8. 低角度鏡頭：從地面仰望
9. 高角度鏡頭：從上方俯瞰
```

#### Prompt 範例

```
Generate a professional 3x3 cinematic storyboard grid showing [subject] in 9 different shots:

Row 1: Wide environmental shot, full view, 3/4 crop (knee-up)
Row 2: Waist-up view, chest-up view, face close-up
Row 3: Macro detail, low-angle, high-angle

All frames with photorealistic texture, consistent cinematic color grading, and proper composition. Same person, same clothes, same lighting across all 9 panels.

生成一個專業的 3x3 電影故事板網格，展示【主體】的 9 個不同鏡頭：

第 1 行：寬廣環境鏡頭、全視圖、3/4 剪輯（膝上景）
第 2 行：腰部以上視圖、胸部以上視圖、臉部特寫
第 3 行：微距細節、低角度、高角度

所有畫面均具有照片般逼真的紋理，一致的電影級調色，以及正確的構圖。所有 9 個面板中是相同的人物、相同的衣服和相同的光照。
```

---

### 3. Pop-Art 風格疊加技巧

在真實照片上疊加 Pop-Art 插畫元素：

#### 基本結構

```json
{
  "base_photo": "photorealistic portrait/scene",
  "art_overlay": {
    "style": "maximalist pop-art",
    "illustrated_elements": {
      "monsters": "cute creatures, food characters",
      "graphic_shapes": "stars, hearts, drips, splashes",
      "style": "flat neon colors with thick black outlines"
    },
    "placement": {
      "behind_subject": "background filled with overlapping elements",
      "around_subject": "elements peeking around edges",
      "over_clothing": "some elements on clothes",
      "avoid_skin": "face and skin remain photorealistic"
    }
  }
}
```

#### 完整範例：街頭 Pop-Art

```
A beautiful young woman sitting on a concrete street barrier, wearing lavender cropped hoodie and mint pleated skirt, white sneakers. Urban street corner setting with bright diffused afternoon light.

Art overlay: Dense maximalist sweets-monster pop-art cluster with banana ghosts, donut creatures, strawberry heads, melting chocolate blobs, cookie beasts, gummy worms in flat neon colors (pink, cyan, lime, yellow, purple) with thick black outlines.

Placement: Entire background packed with overlapping monsters, creatures peeking near shoulders and feet, some resting on clothes. Face, legs, and arms remain clean and photorealistic. Layers in front and behind create stacked chaotic depth with glowing rim lines and motion effects.

Style: Pastel street photography with maximalist pop-art overlay. Skin photorealistic, clothing realistic, illustration flat vector style.
```

---

### 4. 建築資訊圖表技巧

將真實照片轉換為技術藍圖風格：

#### Prompt 模板

```
Create an infographic image of [LANDMARK], combining a real photograph with blueprint-style technical annotations.

Include:
- Title in a hand-drawn box
- White chalk-style sketches showing:
  * Key structural data
  * Important measurements
  * Material quantities
  * Internal diagrams
  * Load-flow arrows
  * Cross-sections
  * Floor plans
  * Notable architectural features

Style: Blueprint aesthetic with white line drawings on the photograph, technical/architectural annotation style, educational infographic feel.

創造【地標】的資訊圖表，結合真實照片與藍圖風格技術註解。

包含：
- 手繪框中的標題
- 白色粉筆風格草圖顯示：
  * 關鍵結構數據
  * 重要尺寸
  * 材料數量
  * 內部圖表
  * 負載流向箭頭
  * 橫截面
  * 平面圖
  * 顯著建築特徵

風格：藍圖美學，照片上有白色線條繪圖，技術/建築註解風格，教育資訊圖表感覺。
```

---

### 5. 室內設計展示板技巧

從 2D 平面圖生成完整的室內設計展示：

#### Prompt 結構

```
Based on the uploaded 2D floor plan, generate a professional interior design presentation board.

Layout: Collage with one large main image at top, several smaller images below.

Content:
1. Main Image (Top): Wide-angle perspective of main living area
2. Small Image (Bottom Left): Master Bedroom view
3. Small Image (Bottom Middle): Home Office/Study room
4. Small Image (Bottom Right): 3D top-down floor plan with furniture

Style: Consistent [Modern Minimalist/Scandinavian/Industrial] style with [flooring type] and [wall color] across ALL images.

Quality: Photorealistic rendering, soft natural lighting.

根據上傳的 2D 平面圖，生成專業室內設計展示板。

佈局：拼貼，頂部一張大主圖，下方幾張小圖。

內容：
1. 主圖（頂部）：主要生活區域的廣角透視圖
2. 小圖（左下）：主臥室視圖
3. 小圖（中下）：家庭辦公室/書房
4. 小圖（右下）：帶家具佈局的 3D 俯視平面圖

風格：所有圖片保持一致的【現代極簡/北歐/工業】風格，【地板類型】和【牆壁顏色】。

品質：寫實渲染，柔和自然光線。
```

---

### 6. 年齡變化技巧

生成同一人物不同年齡的照片：

```
Generate the holiday photo of this person through the ages up to 80 years old.

Show the same person at ages: 20, 30, 40, 50, 60, 70, 80.
Maintain recognizable features while showing natural aging.
Same holiday setting and lighting across all ages.
Photorealistic, natural aging progression.

生成此人從現在到 80 歲的節日照片。

顯示同一人在以下年齡：20、30、40、50、60、70、80 歲。
保持可識別的特徵，同時顯示自然老化。
所有年齡保持相同的節日場景和光線。
寫實，自然的老化過程。
```

---

### 7. 促銷海報文字整合技巧

創造包含完美文字的專業海報：

#### Prompt 模板

```
Design a professional promotional poster for a [Business Type].

Composition: [Scene description with focal point]

Text Integration:
1. Main Title: '[Title Text]' in [font style] at the top
2. Offer: '[Offer Text]' in [badge/sticker style] on the side
3. Footer: '[Footer Text]' in small clean text at the bottom

Quality: Ensure all text is perfectly spelled, centered, and integrated into the image's depth of field.

為【業務類型】設計專業促銷海報。

構圖：【場景描述與焦點】

文字整合：
1. 主標題：頂部的【字體風格】'【標題文字】'
2. 優惠：側邊【徽章/貼紙風格】的'【優惠文字】'
3. 頁腳：底部小而乾淨的文字'【頁腳文字】'

品質：確保所有文字拼寫完美、居中，並整合到圖片的景深中。
```

#### 實際範例：咖啡店促銷

```
Design a professional promotional poster for a Coffee Shop.

Composition: Cinematic close-up of a steaming cappuccino on rustic wooden table, autumn leaves in background (cozy atmosphere).

Text Integration:
1. Main Title: 'Autumn Special' in elegant gold serif typography at the top
2. Offer: 'Buy One Get One Free' in modern badge style on the side
3. Footer: 'Limited Time Only' in small clean text at the bottom

Quality: Photorealistic, warm lighting, all text perfectly integrated.
```

---

### 8. 動漫轉真人技巧

將動漫角色轉換為真人照片：

```
Transform this anime/cartoon character into a photorealistic human portrait.

Maintain:
- Character's distinctive features
- Hair color and style
- Eye color and shape
- Facial structure
- Clothing style

Convert to:
- Realistic skin texture
- Natural lighting
- Photographic quality
- Human proportions

Style: Professional portrait photography, natural lighting, high detail.

將此動漫/卡通角色轉換為寫實人像照片。

保持：
- 角色的獨特特徵
- 髮色和髮型
- 眼睛顏色和形狀
- 臉部結構
- 服裝風格

轉換為：
- 真實皮膚質感
- 自然光線
- 攝影品質
- 人類比例

風格：專業人像攝影，自然光線，高細節。
```

---

## 📝 注意事項

1. **替換佔位符**：所有 [ ] 中的內容都需要替換為具體描述
2. **圖片編號**：[Image1]、[Image2] 等表示需要上傳的圖片
3. **語言選擇**：中文和英文 prompt 效果可能略有不同，建議測試
4. **版權問題**：生成的圖片請注意版權和使用規範

---

## 🌟 Nano Banana 的優勢

### vs 傳統 AI 圖片生成

| 項目 | 傳統 AI | Nano Banana |
|------|---------|-------------|
| **編輯方式** | 需要重新生成 | 對話式編輯，即時修改 |
| **多圖處理** | 通常只能單圖 | 可同時處理多張圖片 |
| **文字生成** | 常常錯誤 | 精準清晰（英文） |
| **邏輯理解** | 基本理解 | 深層邏輯推理 |
| **互動性** | 單向生成 | 雙向對話優化 |

### 適合的使用場景

- ✅ 需要快速迭代的設計工作
- ✅ 多圖合成和風格轉換
- ✅ 產品圖片編輯和優化
- ✅ 創意探索和概念設計
- ✅ 社交媒體內容創作

---

## 💡 最佳實踐

### 1. 從簡單開始，逐步細化

```
第一步：「一隻貓」
第二步：「幫牠戴上紅色帽子」
第三步：「讓背景變成花園」
第四步：「增加陽光效果」
```

### 2. 善用對話式編輯

```
不要：重新生成整張圖
要：「把這個顏色改成藍色」
```

### 3. 明確指定細節

```
模糊：「讓圖片更好看」
清晰：「增加亮度 20%，提高對比度，讓天空更藍」
```

### 4. 利用多圖功能

```
「將第一張圖的人物放到第二張圖的背景中」
「結合這三張圖的元素，創造一個新場景」
```

### 5. 保存成功的 Prompt

```
將效果好的 Prompt 記錄下來
建立自己的 Prompt 資料庫
持續優化和擴充
```

---

## ❓ 常見問題

### Q1: Nano Banana 是免費的嗎？

**A**: 目前在 Google AI Studio 和 Gemini 平台上可以免費使用，但可能有使用限制。

### Q2: 中文 Prompt 效果好還是英文好？

**A**: 兩者都支援，但英文 Prompt 通常更精確。建議：
- 複雜需求：使用英文
- 簡單需求：中文即可
- 最佳做法：提供中英文雙語 Prompt

### Q3: 生成的圖片可以商用嗎？

**A**: 請查看 Google 的使用條款。一般來說：
- 個人使用：通常沒問題
- 商業使用：需要確認授權
- 建議：使用前閱讀最新的服務條款

### Q4: 如何提高生成品質？

**A**: 
1. 提供詳細的描述
2. 指定具體的風格和參數
3. 使用參考圖片
4. 逐步優化而非一次到位
5. 參考本文件的 Prompt 範例

### Q5: 為什麼有時候生成失敗？

**A**: 可能原因：
- Prompt 過於複雜或矛盾
- 包含敏感內容
- 服務器繁忙
- 網路問題

**解決方法**：
- 簡化 Prompt
- 分步驟生成
- 稍後再試
- 檢查網路連線

---

## 🔗 相關資源

### 官方文件
- [Google AI Studio 文件](https://ai.google.dev/)
- [Gemini API 文件](https://ai.google.dev/gemini-api/docs)

### 學習資源
- [Fotor AI 教學](https://www.fotor.com/tw/blog/)
- [Prompt 工程指南](https://www.promptingguide.ai/)

### 社群資源
- [Reddit - r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/)
- [Discord - AI Art Community](https://discord.gg/stablediffusion)

---

## 📊 更新日誌

### 2025-12-11 v1.3
- ✅ 新增進階 Prompt 技巧章節
- ✅ JSON 格式 Prompt（結構化控制）
- ✅ 電影分鏡技巧（3x3 故事板）
- ✅ Pop-Art 風格疊加
- ✅ 建築資訊圖表
- ✅ 室內設計展示板
- ✅ 年齡變化技巧
- ✅ 促銷海報文字整合
- ✅ 動漫轉真人技巧
- ✅ 建立 url.md 資源清單

### 2025-12-11 v1.2
- ✅ 新增產業專屬 Prompt 章節
- ✅ 包含 9 大產業：電商、餐飲、教育、房地產、時尚、醫療、科技、旅遊、社交媒體
- ✅ 每個產業提供 2-3 個實用 Prompt 範例
- ✅ 更新 prompt-optimizer.md，加入產業專屬優化模板
- ✅ 新增產業優化技巧

### 2025-12-11 v1.1
- ✅ 添加 Nano Banana 詳細介紹
- ✅ 整理 30+ 個 Prompt 範例
- ✅ 添加使用技巧和最佳實踐
- ✅ 添加常見問題解答
- ✅ 添加相關資源連結

---

## 🙏 貢獻

如果你有好用的 Prompt，歡迎分享！

**分享方式**：
1. 測試並驗證 Prompt 效果
2. 記錄 Prompt 和生成結果
3. 添加到本文件
4. 註明來源和用途

---

**資料來源**：
- [Fotor - 40+最熱門 Nano Banana Prompt](https://www.fotor.com/tw/blog/nano-banana-model-prompts/)
- [iBest - Nano Banana 教學](https://www.ibest.com.tw/news-detail/nano-banana-ai/)
- [Master Concept - 產業專屬 Prompts](https://masterconcept.ai/zh-hant/learning-column/google-cloud-zh-hant/google-ais-nano-banana-unlocked-steal-these-prompts-for-your-industry/)
- [Nano Banana Prompt Gallery](https://nanobananaprompt.org/prompts/)

**整理日期**：2025-12-11

**版本**：v1.3 - 新增進階 Prompt 技巧（JSON 格式、電影分鏡、Pop-Art、建築圖表、室內設計、年齡變化、促銷海報、動漫轉真人）
