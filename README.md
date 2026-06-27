---
title: RollOrNot — Support / 支援 / 支持
permalink: /support/
---

# RollOrNot — Support / 支援 / 支持

---

> **Language / 语言**: [English](#english) · [简体中文](#简体中文) · [繁體中文](#繁體中文)

---

## English

### Welcome to RollOrNot Support

Thank you for using RollOrNot! We're here to help you get the most out of your AI-powered study companion.

---

### Frequently Asked Questions

#### 1. How do I set up a local AI model?

RollOrNot supports **local AI models only**. To use AI features, configure a local model in the app.

1. Install and run a local AI service on your device or local network (e.g., Ollama, LM Studio, or llama.cpp)
2. Open the app and go to **Settings** → **AI Model Configuration**
3. Tap **Add** to add a new local model
4. Enter the model name and local base URL (e.g., `http://localhost:11434` for Ollama)
5. Tap **Save** and test the connection
6. Select this as the active model

> **Note**: The app supports local AI models (Ollama, LM Studio, llama.cpp). Make sure your local model service is running before using AI features.

#### 2. Why is AI analysis not working?

- Check that you have configured a local AI model in **Settings** → **AI Model Configuration**
- Ensure your local AI model service (Ollama, LM Studio, or llama.cpp) is running
- Verify that the base URL and model name are correct
- Try testing the connection in **Settings** → **AI Model Configuration** → tap the model → **Test Connection**

#### 3. How do I scan objects with LiDAR?

LiDAR 3D scanning is only available on devices with a LiDAR sensor (iPhone 12 Pro and later Pro/Pro Max models, iPad Pro 2020 and later).

1. Go to the **AR Scan** tab
2. Follow the on-screen guidance to scan the object from multiple angles
3. The real-time mesh quality indicator shows scanning progress
4. Tap **Scan Complete** when finished
5. Preview the 3D model and optionally run AI analysis

#### 4. How do I export mind maps?

1. Open a mind map from any chapter or book
2. Tap the **Export** button in the top-right corner
3. Choose your preferred format: **PNG**, **SVG**, or **PDF**
4. Share the exported file or save it to Files

#### 5. How do I back up my data?

1. Go to **Settings** → **Backup & Restore**
2. Tap **Create Backup**
3. (Optional) Set a password for encryption
4. Save the backup file to iCloud Drive, Files, or share it

To restore:
1. Go to **Settings** → **Backup & Restore**
2. Tap **Restore** and select a backup file
3. Enter the password if the backup is encrypted

#### 6. How do I change the app language?

1. Go to **Settings** → **Language**
2. Select your preferred language: **English**, **简体中文**, or **繁體中文**
3. Tap **Confirm** in the top-right corner
4. The app switches immediately — no restart required

#### 7. Where is my data stored?

All user data is stored locally on your device:
- Structured data: SwiftData local database
- Images and game files: App sandbox file system (`Documents/RollOrNot/`)
- No data is uploaded to any developer-controlled server

#### 8. Can I use the app without an internet connection?

Yes, with limitations:
- **With local models**: If you have a local AI service running (Ollama, LM Studio, or llama.cpp), all AI features work fully offline
- **Without any AI model**: You can still browse your question bank, view saved content, and manage chapters

#### 9. Does the app collect my personal data?

No. RollOrNot does not collect any personal data, usage analytics, or telemetry. All data stays on your device. When you trigger AI analysis, your question text/images are sent directly to your configured AI provider — we never see or store that data.

#### 10. How do I print questions or chapters?

1. Open the question detail, chapter content, or assessment page
2. Tap the **Print** button
3. The print preview automatically removes answers, leaving blank question formats
4. Send to any AirPrint-compatible printer

#### 11. How do I capture questions by photo?

You can capture homework or exam questions by taking a photo or importing from your photo library.

**Method 1: Take a photo**
1. Open the app and go to the **Question Capture** tab
2. Tap the camera button to open the viewfinder
3. Point the camera at the question — make sure the text is well-lit and in focus
4. The app auto-detects the subject (Math, Physics, Chemistry, etc.)
5. Tap the shutter button to capture
6. Wait for OCR processing to extract the text

**Method 2: Import from photo library**
1. Tap the gallery icon in the **Question Capture** tab
2. Select one or more images from your photo library
3. The app supports up to 5 images at once with parallel OCR

**Method 3: Paste text directly**
1. Tap the text input area in the **Question Capture** tab
2. Paste copied text directly

> **Tip**: After capturing, you can run AI analysis on the question, save it to your question bank, or generate similar practice questions.

#### 12. How do I create interactive learning games and scene animations?

RollOrNot can generate interactive HTML5 learning games from your chapter content or study materials. The games use scene animations to explain abstract concepts visually.

**Method 1: Generate games from chapter knowledge points**
1. Open a chapter or study book in the app
2. Tap the **Games** button (🎮 icon) in the chapter toolbar
3. The AI automatically extracts key knowledge points from the chapter content
4. Select a game type:
   - **Word Fill**: Fill in missing words in key concepts
   - **Math Quiz**: Test your math skills with generated problems
   - **Memory Match**: Match related concepts and definitions
   - **Cannon Shooter**: Shoot answers at target questions
   - **Cake Slingshot**: Launch cakes at correct answers
5. Tap **Start Game** to begin playing
6. After completing a game, you can generate a new one with different questions

**Method 2: Photo-to-Game**
1. Go to the **Question Capture** tab
2. Take a photo or import an image of study material
3. After OCR processing, tap the **Generate Game** option
4. The AI creates a learning game based on the content in the photo
5. Choose your preferred game type and start playing

**Method 3: Generate from any saved question**
1. Open a saved question from your question bank
2. Tap the **More** menu (⋯)
3. Select **Generate Game**
4. The AI creates a game based on that question's topic
> **Note**: Scene animations are built into the games — abstract concepts are visualized through animated scenes that make learning more intuitive. The games apply Bloom's Taxonomy and spaced repetition for optimal learning.

---

### Contact Us

If you need further assistance, please reach out:

- **Email**: [waynewgl1987@gmail.com](mailto:waynewgl1987@gmail.com)
- **Response time**: We typically respond within 24–48 hours on business days

When contacting support, please include:
- Your device model and iOS version
- A brief description of the issue
- Steps to reproduce the problem (if applicable)
- Screenshots (if helpful)

---

### Troubleshooting Tips

| Issue | Suggested Solution |
|-------|-------------------|
| App crashes on launch | Restart your device and ensure you're running iOS 17.0+ |
| Camera not working | Check camera permissions in **Settings** → **Privacy** → **Camera** → **RollOrNot** |
| AI response is too slow | Try a faster model or reduce `Max Tokens` in AI provider settings |
| Scanner not detecting objects | Ensure adequate lighting and hold the device 0.3–1.5m from the object |
| Backup fails | Ensure you have sufficient free storage space on your device |

---

### Version Information

- **Current Version**: 1.0.0
- **Minimum iOS**: 17.0
- **Supported Devices**: iPhone, iPad
- **Languages**: English, Simplified Chinese, Traditional Chinese

---

*Last updated: June 2026*

---

## 简体中文

### 欢迎使用 RollOrNot 支持页面

感谢您使用 RollOrNot（卷不卷）！我们致力于为您提供帮助，让您充分发挥这款 AI 智能学习助手的作用。

---

### 常见问题

#### 1. 如何配置本地 AI 大模型？

RollOrNot 仅支持**本地 AI 大模型**服务。使用 AI 功能前，请先配置本地模型。

1. 在设备或本地网络中安装并启动本地 AI 服务（如 Ollama、LM Studio 或 llama.cpp）
2. 打开 App，前往 **设置** → **AI 模型配置**
3. 点击 **添加** 以添加本地模型
4. 输入模型名称和本地地址（例如 Ollama 默认为 `http://localhost:11434`）
5. 点击 **保存** 并测试连接
6. 将该模型设为启用

> **注意**：本 App 仅支持本地 AI 大模型（Ollama、LM Studio、llama.cpp）。使用 AI 功能前，请确保本地模型服务已启动。

#### 2. 为什么 AI 分析无法使用？

- 请确认您已在 **设置** → **AI 模型配置** 中配置了本地 AI 大模型
- 确保本地 AI 模型服务（Ollama、LM Studio 或 llama.cpp）正在运行
- 检查模型地址和模型名称是否正确
- 可在 **设置** → **AI 模型配置** → 点击该模型 → **测试连接** 进行验证

#### 3. 如何使用 LiDAR 扫描物体？

LiDAR 3D 扫描仅在配备 LiDAR 传感器的设备上可用（iPhone 12 Pro 及后续 Pro/Pro Max 机型、iPad Pro 2020 及后续机型）。

1. 前往 **AR 扫描** 标签页
2. 按照屏幕引导从多个角度扫描物体
3. 实时网格质量指示器会显示扫描进度
4. 完成后点击 **扫描完成**
5. 预览 3D 模型，可选执行 AI 分析

#### 4. 如何导出思维导图？

1. 从章节或书本中打开思维导图
2. 点击右上角的 **导出** 按钮
3. 选择格式：**PNG**、**SVG** 或 **PDF**
4. 分享或保存到文件

#### 5. 如何备份数据？

1. 前往 **设置** → **备份与恢复**
2. 点击 **创建备份**
3. （可选）设置加密密码
4. 将备份文件保存到 iCloud 云盘、文件或分享

恢复备份：
1. 前往 **设置** → **备份与恢复**
2. 点击 **恢复** 并选择备份文件
3. 若备份有加密，请输入密码

#### 6. 如何切换语言？

1. 前往 **设置** → **语言**
2. 选择您偏好的语言：**English**、**简体中文** 或 **繁體中文**
3. 点击右上角的 **确认**
4. App 会立即切换，无需重新启动

#### 7. 我的数据存储在哪里？

所有用户数据均存储在设备本地：
- 结构化数据：SwiftData 本地数据库
- 图片与游戏文件：App 沙箱文件系统（`Documents/RollOrNot/`）
- 不上传任何数据至开发者服务器

#### 8. 没有网络时可以使用 App 吗？

可以，但有一定限制：
- **本地大模型**：若您有本地 AI 服务（Ollama、LM Studio 或 llama.cpp），所有 AI 功能均可完全离线使用
- **不使用任何 AI 模型**：仍可浏览题库、查看已保存内容和管理章节

#### 9. App 会收集我的个人数据吗？

不会。RollOrNot 不收集任何个人数据、使用分析或遥测信息。所有数据均留在您的设备上。当您触发 AI 分析时，题目文字/图片会直接发送至您配置的 AI 提供商——我们不会访问或存储这些数据。

#### 10. 如何打印题目或章节？

1. 打开题目详情、章节内容或评测页面
2. 点击 **打印** 按钮
3. 打印预览会自动移除答案，保留空白题目格式
4. 发送至支持 AirPrint 的打印机

#### 11. 如何拍照收题？

您可以通过拍照或从相册导入的方式收录题目。

**方法一：拍照**
1. 打开 App，进入 **拍题** 标签页
2. 点击相机按钮打开取景器
3. 将相机对准题目——确保文字光线充足、画面清晰
4. App 会自动检测学科（数学、物理、化学等）
5. 点击快门按钮拍摄
6. 等待 OCR 识别完成，提取题目文字

**方法二：从相册导入**
1. 在 **拍题** 标签页点击相册图标
2. 从相册中选择一张或多张图片
3. App 支持最多同时导入 5 张图片，OCR 并行识别

**方法三：直接粘贴文字**
1. 在 **拍题** 标签页点击文字输入区域
2. 直接粘贴复制的文字
> **提示**：拍摄完成后，您可以对题目运行 AI 分析、保存到题库，或生成同类练习题。

#### 12. 如何创建互动学习游戏和情景动画？

RollOrNot 可以根据章节内容或学习资料，自动生成 HTML5 互动学习游戏。游戏中的情景动画可以直观展示抽象概念。

**方法一：从章节知识点生成游戏**
1. 在 App 中打开一个章节或学习书册
2. 点击章节工具栏中的 **游戏** 按钮（🎮 图标）
3. AI 自动从章节内容提取关键知识点
4. 选择游戏类型：
   - **填字游戏**：填写关键概念中的缺失词语
   - **数学测验**：通过生成的题目测试数学能力
   - **记忆配对**：配对相关的概念和定义
   - **弹射打靶**：将答案射向目标题目
   - **蛋糕弹弓**：将蛋糕弹向正确答案
5. 点击 **开始游戏** 开始玩
6. 完成后可生成新的游戏，题目会变化

**方法二：拍照生成游戏**
1. 前往 **拍题** 标签页
2. 拍摄或导入学习资料的图片
3. OCR 识别完成后，点击 **生成游戏** 选项
4. AI 根据照片内容创建学习游戏
5. 选择偏好的游戏类型开始玩

**方法三：从已保存题目生成游戏**
1. 从题库中打开一个已保存的题目
2. 点击 **更多** 菜单（⋯）
3. 选择 **生成游戏**
4. AI 根据该题目的知识点创建游戏
> **说明**：情景动画嵌入在游戏中，通过动画场景直观展示抽象概念，让学习更直观。游戏应用了 Bloom 认知分类法和间隔重复技术，优化学习效果。

---

### 联系我们

如果您需要进一步协助，请通过以下方式联系我们：

- **电子邮件**：[waynewgl1987@gmail.com](mailto:waynewgl1987@gmail.com)
- **回复时间**：我们通常会在 24–48 个工作小时内回复

联系支持时，请提供：
- 您的设备型号与 iOS 版本
- 问题的简要描述
- 重现问题的步骤（如适用）
- 屏幕截图（如有帮助）

---

### 故障排除建议

| 问题 | 建议解决方案 |
|------|------------|
| App 启动时闪退 | 重新启动设备，确保运行 iOS 17.0+ |
| 相机无法使用 | 检查 **设置** → **隐私与安全性** → **相机** → **RollOrNot** 权限 |
| AI 响应过慢 | 尝试使用更快的模型，或在 AI 提供商设置中降低「最大 Token 数」 |
| 扫描器无法检测物体 | 确保光线充足，设备距离物体 0.3–1.5 米 |
| 备份失败 | 确保设备有足够的可用存储空间 |

---

### 版本信息

- **当前版本**：1.0.0
- **最低系统要求**：iOS 17.0
- **支持设备**：iPhone、iPad
- **支持语言**：英文、简体中文、繁体中文

---

*最后更新：2026 年 6 月*

---

## 繁體中文

### 歡迎使用 RollOrNot 支援頁面

感謝您使用 RollOrNot（卷不卷）！我們竭誠為您提供協助，讓您充分發揮這款 AI 智能學習夥伴的功用。

---

### 常見問題

#### 1. 如何設定本地 AI 大型模型？

RollOrNot 僅支援**本地 AI 大型模型**服務。使用 AI 功能前，請先設定本地模型。

1. 在裝置或本地網路中安裝並啟動本地 AI 服務（如 Ollama、LM Studio 或 llama.cpp）
2. 打開 App，前往 **設定** → **AI 模型配置**
3. 點擊 **新增** 以新增本地模型
4. 輸入模型名稱和本地網址（例如 Ollama 預設為 `http://localhost:11434`）
5. 點擊 **儲存** 並測試連線
6. 將該模型設為啟用

> **注意**：本 App 僅支援本地 AI 大型模型（Ollama、LM Studio、llama.cpp）。使用 AI 功能前，請確保本地模型服務已啟動。

#### 2. 為什麼 AI 分析無法使用？

- 請確認您已在 **設定** → **AI 模型配置** 中設定了本地 AI 大型模型
- 確保本地 AI 模型服務（Ollama、LM Studio 或 llama.cpp）正在執行
- 檢查模型網址和模型名稱是否正確
- 可在 **設定** → **AI 模型配置** → 點擊該模型 → **測試連線** 進行驗證

#### 3. 如何使用 LiDAR 掃描物體？

LiDAR 3D 掃描僅在配備 LiDAR 感測器的裝置上可用（iPhone 12 Pro 及後續 Pro/Pro Max 機型、iPad Pro 2020 及後續機型）。

1. 前往 **AR 掃描** 標籤頁
2. 依照螢幕引導從多個角度掃描物體
3. 即時網格品質指示器會顯示掃描進度
4. 完成後點擊 **掃描完成**
5. 預覽 3D 模型，可選執行 AI 分析

#### 4. 如何匯出思維導圖？

1. 從章節或書本中開啟思維導圖
2. 點擊右上角的 **匯出** 按鈕
3. 選擇格式：**PNG**、**SVG** 或 **PDF**
4. 分享或儲存到檔案

#### 5. 如何備份資料？

1. 前往 **設定** → **備份與恢復**
2. 點擊 **建立備份**
3. （可選）設定加密密碼
4. 將備份檔案儲存到 iCloud 雲碟、檔案或分享

恢復備份：
1. 前往 **設定** → **備份與恢復**
2. 點擊 **恢復** 並選擇備份檔案
3. 若備份有加密，請輸入密碼

#### 6. 如何切換語言？

1. 前往 **設定** → **語言**
2. 選擇您偏好的語言：**English**、**简体中文** 或 **繁體中文**
3. 點擊右上角的 **確認**
4. App 會立即切換，無需重新啟動

#### 7. 我的資料儲存在哪裡？

所有使用者資料均儲存在裝置本地：
- 結構化資料：SwiftData 本地資料庫
- 圖片與遊戲檔案：App 沙箱檔案系統（`Documents/RollOrNot/`）
- 不上傳任何資料至開發者伺服器

#### 8. 沒有網路時可以使用 App 嗎？

可以，但有部分限制：
- **本地大型模型**：若您有本機 AI 服務（Ollama、LM Studio 或 llama.cpp），所有 AI 功能皆可完全離線使用
- **不使用任何 AI 模型**：仍可瀏覽題庫、查看已儲存內容和管理章節

#### 9. App 會收集我的個人資料嗎？

不會。RollOrNot 不收集任何個人資料、使用分析或遙測資訊。所有資料均留在您的裝置上。當您觸發 AI 分析時，題目文字/圖片會直接傳送至您配置的 AI 提供商——我們不會存取或儲存這些資料。

#### 10. 如何列印題目或章節？

1. 開啟題目詳情、章節內容或評測頁面
2. 點擊 **列印** 按鈕
3. 列印預覽會自動移除答案，保留空白題目格式
4. 傳送至支援 AirPrint 的印表機

#### 11. 如何拍照收題？

您可以透過拍照或從相簿匯入的方式收錄題目。

**方法一：拍照**
1. 打開 App，進入 **拍題** 標籤頁
2. 點擊相機按鈕開啟觀景窗
3. 將相機對準題目——確保文字光線充足、畫面清晰
4. App 會自動偵測學科（數學、物理、化學等）
5. 點擊快門按鈕拍攝
6. 等待 OCR 辨識完成，提取題目文字

**方法二：從相簿匯入**
1. 在 **拍題** 標籤頁點擊相簿圖示
2. 從相簿中選擇一張或多張圖片
3. App 支援最多同時匯入 5 張圖片，OCR 並行辨識

**方法三：直接貼上文字**
1. 在 **拍題** 標籤頁點擊文字輸入區域
2. 直接貼上複製的文字
> **提示**：拍攝完成後，您可以對題目執行 AI 分析、儲存到題庫，或產生同類練習題。

#### 12. 如何建立互動學習遊戲和情景動畫？

RollOrNot 可以根據章節內容或學習資料，自動產生 HTML5 互動學習遊戲。遊戲中的情景動畫可以直觀展示抽象概念。

**方法一：從章節知識點產生遊戲**
1. 在 App 中開啟一個章節或學習書冊
2. 點擊章節工具列中的 **遊戲** 按鈕（🎮 圖示）
3. AI 自動從章節內容提取關鍵知識點
4. 選擇遊戲類型：
   - **填字遊戲**：填寫關鍵概念中的缺失詞語
   - **數學測驗**：透過產生的題目測試數學能力
   - **記憶配對**：配對相關的概念和定義
   - **彈射打靶**：將答案射向目標題目
   - **蛋糕彈弓**：將蛋糕彈向正確答案
5. 點擊 **開始遊戲** 開始玩
6. 完成後可產生新的遊戲，題目會變化

**方法二：拍照產生遊戲**
1. 前往 **拍題** 標籤頁
2. 拍攝或匯入學習資料的圖片
3. OCR 辨識完成後，點擊 **產生遊戲** 選項
4. AI 根據照片內容建立學習遊戲
5. 選擇偏好的遊戲類型開始玩

**方法三：從已儲存題目產生遊戲**
1. 從題庫中開啟一個已儲存的題目
2. 點擊 **更多** 選單（⋯）
3. 選擇 **產生遊戲**
4. AI 根據該題目的知識點建立遊戲
> **說明**：情景動畫嵌入在遊戲中，透過動畫場景直觀展示抽象概念，讓學習更直觀。遊戲應用了 Bloom 認知分類法和間隔重複技術，最佳化學習效果。

---

### 聯絡我們

如果您需要進一步協助，請透過以下方式聯絡：

- **電子郵件**：[waynewgl1987@gmail.com](mailto:waynewgl1987@gmail.com)
- **回覆時間**：我們通常會在 24–48 個工作小時內回覆

聯絡支援時，請提供：
- 您的裝置型號與 iOS 版本
- 問題的簡要描述
- 重現問題的步驟（如適用）
- 螢幕截圖（如有幫助）

---

### 故障排除建議

| 問題 | 建議解決方案 |
|------|------------|
| App 啟動時閃退 | 重新啟動裝置，確保運行 iOS 17.0+ |
| 相機無法使用 | 檢查 **設定** → **隱私權** → **相機** → **RollOrNot** 權限 |
| AI 回應過慢 | 嘗試使用較快的模型，或在 AI 提供商設定中降低「最大 Token 數」|
| 掃描器無法偵測物體 | 確保光線充足，裝置距離物體 0.3–1.5 公尺 |
| 備份失敗 | 確保裝置有足夠的可用儲存空間 |

---

### 版本資訊

- **目前版本**：1.0.0
- **最低系統需求**：iOS 17.0
- **支援裝置**：iPhone、iPad
- **支援語言**：英文、簡體中文、繁體中文

---

*最後更新：2026 年 6 月*
