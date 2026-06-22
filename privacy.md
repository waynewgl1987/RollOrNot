# RollOrNot — Privacy Policy / 隐私政策 / 隱私權政策

---

> **Language / 语言**: [English](#english) · [简体中文](#简体中文) · [繁體中文](#繁體中文)

---

## English

**Last updated**: June 22, 2026

---

### Introduction

RollOrNot ("the App") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use our application.

**Our core principle is simple: We do not collect your data.** All user data is stored locally on your device, and we do not operate any servers that receive or store your personal information.

---

### 1. Information We Collect

#### 1.1 Information You Provide

The App processes the following data locally on your device:

- **Question content**: Text and images of homework, exam questions, or study materials that you capture or import
- **AI analysis results**: Solutions, explanations, and generated content produced by AI services
- **Personal notes**: Notes and annotations you create within the App
- **AR scan data**: 3D scan results from device LiDAR sensor

All of this data is stored exclusively in your device's local storage (SwiftData database and file system).

#### 1.2 Automatically Collected Information

We do **not** collect any of the following:
- Device identifiers (UDID, IDFA, IDFV)
- IP addresses
- Usage analytics or telemetry
- Crash reports
- Location data
- Contact information
- Browsing history
- Any other personal data

#### 1.3 No Account System

The App does **not** require registration, account creation, or sign-in of any kind. There is no user profile, no password, and no account management system.

---

### 2. How We Use Your Information

Since we do not collect any data to our servers, the only processing that occurs is:

- **Local processing**: Question analysis, game generation, mind map creation — all performed by AI services you configure, with data sent directly from your device to your chosen AI provider
- **On-device storage**: Saving your questions, notes, and settings to your device's local storage for future access

We do not use your data for training, advertising, analytics, or any other purpose.

---

### 3. Camera & Photo Library Access

The App requests access to your device's camera and photo library solely for the purpose of capturing or importing question images:

| Permission | Purpose | Required? |
|------------|---------|-----------|
| **Camera** | Photograph homework, exam papers, textbook pages, or objects for AR scanning | Yes, for camera features |
| **Photo Library (Read)** | Import existing images from your photo library | Yes, for gallery import |
| **Photo Library (Write)** | Save exported mind map PNG images to your photo library | Optional |

These permissions are requested **only when you first use the corresponding feature**. You can manage or revoke these permissions at any time in your device's **Settings** → **Privacy**.

We do not access your camera or photo library for any purpose other than what you explicitly initiate within the App.

---

### 4. AI Service Providers

When you trigger AI analysis features, the question text and/or images are sent directly from your device to the third-party AI service provider you have configured in the App's settings. This happens **only when you explicitly initiate an AI action**.

**Important notes:**

- You must provide your own API key for your chosen AI provider(s). The App does not supply AI model quota.
- The AI providers you configure (OpenAI, DeepSeek, Google Gemini, Claude, etc.) have their own privacy policies governing how they handle data sent to their services.
- We recommend reviewing the privacy policy of your chosen AI provider(s) for details on their data handling practices.
- If you use a local AI model (Ollama, LM Studio, llama.cpp), no data leaves your device.
- The App does not have access to the API keys you store in its settings — they are saved locally on your device.

**List of supported AI providers** (each operates under its own privacy policy):
- OpenAI
- DeepSeek
- Google Gemini
- Anthropic (Claude)
- Alibaba Cloud (Qwen / 通义千问)
- ByteDance (Doubao / 豆包)
- ZhipuAI (智谱清言)
- GitHub Copilot
- Ollama (local)
- LM Studio (local)
- llama.cpp (local)

---

### 5. Third-Party Services

The App uses the following third-party software components embedded in the app bundle (no data is sent to their servers):

| Component | Purpose | Data Sent |
|-----------|---------|-----------|
| [marked.js](https://github.com/markedjs/marked) | Markdown rendering | None (local only) |
| [KaTeX](https://github.com/KaTeX/KaTeX) | Math formula rendering | None (local only) |
| [Mermaid](https://github.com/mermaid-js/mermaid) | Diagram rendering | None (local only) |

All components are included locally in the app bundle — no network requests are made to their servers.

---

### 6. Data Storage & Security

- **All data is stored locally** on your device using SwiftData (local database) and the app's sandbox file system
- **Encrypted backups**: When you choose to create a backup, data is encrypted using AES-256-GCM with an optional password you provide
- **No cloud sync**: The App does not sync data to any cloud service
- **Data deletion**: Uninstalling the App removes all locally stored data. You can also clear data via the App's **Settings** → **Cache Management**

---

### 7. Children's Privacy

The App is designed for students and learners of all ages. Since we do not collect any personal information, there is no risk of inadvertent data collection from children. The App does not contain any age-restricted content.

---

### 8. Data Deletion

Since all data is stored locally on your device, you can delete your data at any time by:

1. Deleting individual items within the App (questions, notes, scans, etc.)
2. Clearing cache in **Settings** → **Cache Management**
3. Uninstalling the App from your device

---

### 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top of this policy. We encourage you to review this policy periodically.

---

### 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:

- **Email**: [rollornot.app@icloud.com](mailto:rollornot.app@icloud.com)
- **Response time**: We typically respond within 24–48 hours on business days

---

## 简体中文

**最后更新**：2026 年 6 月 22 日

---

### 引言

RollOrNot（卷不卷）（以下简称"本 App"）致力于保护您的隐私。本隐私政策说明您在使用本 App 时我们如何收集、使用和保护您的信息。

**我们的核心原则很简单：我们不收集您的数据。** 所有用户数据均存储在您的设备本地，我们不运营任何接收或存储您个人信息的服务器。

---

### 1. 我们收集的信息

#### 1.1 您提供的信息

本 App 在您的设备本地处理以下数据：

- **题目内容**：您拍摄或导入的作业、试题或学习资料的文字和图片
- **AI 分析结果**：由 AI 服务生成的解答、讲解和生成内容
- **个人笔记**：您在本 App 内创建的笔记和标注
- **AR 扫描数据**：来自设备 LiDAR 传感器的 3D 扫描结果

所有这些数据仅存储在您的设备本地存储中（SwiftData 数据库和文件系统）。

#### 1.2 自动收集的信息

我们**不**收集以下任何信息：
- 设备标识符（UDID、IDFA、IDFV）
- IP 地址
- 使用分析或遥测数据
- 崩溃报告
- 位置数据
- 联系信息
- 浏览历史
- 任何其他个人数据

#### 1.3 无账号系统

本 App **不**要求注册、创建账号或登录。没有任何用户档案、密码或账号管理系统。

---

### 2. 我们如何使用您的信息

由于我们不向自己的服务器收集任何数据，唯一的处理行为是：

- **本地处理**：题目分析、游戏生成、思维导图创建——均由您配置的 AI 服务执行，数据从您的设备直接发送至您选择的 AI 提供商
- **设备端存储**：将您的题目、笔记和设置保存到设备本地存储，方便后续访问

我们不会将您的数据用于训练、广告、分析或任何其他目的。

---

### 3. 相机与相册访问权限

本 App 请求访问您的相机和相册，仅用于拍摄或导入题目图片：

| 权限 | 用途 | 是否必需？ |
|------|------|-----------|
| **相机** | 拍摄作业、试卷、教材页面或 AR 扫描物体 | 是，用于相机功能 |
| **相册（读取）** | 从相册导入已有图片 | 是，用于相册导入 |
| **相册（写入）** | 将导出的思维导图 PNG 保存到相册 | 可选 |

这些权限仅在**您首次使用对应功能时**请求。您可以随时在设备的 **设置** → **隐私与安全性** 中管理或撤销这些权限。

除您在本 App 内明确触发的操作外，我们不会以任何其他目的访问您的相机或相册。

---

### 4. AI 服务提供商

当您触发 AI 分析功能时，题目文字和/或图片会从您的设备直接发送至您在 App 设置中配置的第三方 AI 服务提供商。这仅在**您明确发起 AI 操作时**发生。

**重要说明：**

- 您需要为您选择的 AI 提供商提供自己的 API 密钥。本 App 不提供 AI 模型额度。
- 您配置的 AI 提供商（OpenAI、DeepSeek、Google Gemini、Claude 等）有自己的隐私政策，管辖他们如何处理发送至其服务的数据。
- 我们建议您查阅所选 AI 提供商的隐私政策，了解其数据处理实践。
- 如果您使用本地 AI 模型（Ollama、LM Studio、llama.cpp），则没有任何数据离开您的设备。
- 本 App 无法访问您存储在设置中的 API 密钥——它们仅保存在您的设备本地。

**支持的 AI 提供商列表**（均按其自身隐私政策运营）：
- OpenAI
- DeepSeek
- Google Gemini
- Anthropic (Claude)
- 阿里云（通义千问）
- 字节跳动（豆包）
- 智谱清言
- GitHub Copilot
- Ollama（本地）
- LM Studio（本地）
- llama.cpp（本地）

---

### 5. 第三方服务

本 App 使用以下内嵌在 App 包中的第三方软件组件（不会向其服务器发送任何数据）：

| 组件 | 用途 | 发送的数据 |
|------|------|-----------|
| [marked.js](https://github.com/markedjs/marked) | Markdown 渲染 | 无（仅本地） |
| [KaTeX](https://github.com/KaTeX/KaTeX) | 数学公式渲染 | 无（仅本地） |
| [Mermaid](https://github.com/mermaid-js/mermaid) | 图表渲染 | 无（仅本地） |

所有组件均包含在 App 包本地——不会向其服务器发起任何网络请求。

---

### 6. 数据存储与安全

- **所有数据均存储在本地**：使用 SwiftData（本地数据库）和 App 沙箱文件系统
- **加密备份**：当您选择创建备份时，数据使用 AES-256-GCM 加密，并可选设置密码
- **无云同步**：本 App 不会将数据同步到任何云服务
- **数据删除**：卸载本 App 会删除所有本地存储的数据。您也可以通过 App 内的 **设置** → **缓存管理** 清除数据

---

### 7. 儿童隐私

本 App 面向各年龄段的学生和学习者设计。由于我们不收集任何个人信息，因此不存在无意中收集儿童数据的风险。本 App 不包含任何年龄限制内容。

---

### 8. 数据删除

由于所有数据均存储在您的设备本地，您可以随时通过以下方式删除数据：

1. 在 App 内删除单个项目（题目、笔记、扫描等）
2. 在 **设置** → **缓存管理** 中清除缓存
3. 从设备卸载本 App

---

### 9. 本隐私政策的变更

我们可能会不时更新本隐私政策。更新时，我们会修改本政策顶部的"最后更新"日期。我们建议您定期审阅本政策。

---

### 10. 联系我们

如果您对本隐私政策或您的数据有任何问题、疑虑或请求，请通过以下方式联系我们：

- **电子邮件**：[rollornot.app@icloud.com](mailto:rollornot.app@icloud.com)
- **回复时间**：我们通常会在 24–48 个工作小时内回复

---

## 繁體中文

**最後更新**：2026 年 6 月 22 日

---

### 引言

RollOrNot（卷不卷）（以下簡稱「本 App」）致力於保護您的隱私。本隱私權政策說明您在使用本 App 時我們如何收集、使用和保護您的資訊。

**我們的核心原則很簡單：我們不收集您的資料。** 所有使用者資料均儲存在您的裝置本地，我們不營運任何接收或儲存您個人資訊的伺服器。

---

### 1. 我們收集的資訊

#### 1.1 您提供的資訊

本 App 在您的裝置本地處理以下資料：

- **題目內容**：您拍攝或匯入的作業、試題或學習資料的文字和圖片
- **AI 分析結果**：由 AI 服務產生的解答、講解和生成內容
- **個人筆記**：您在本 App 內建立的筆記和標註
- **AR 掃描資料**：來自裝置 LiDAR 感測器的 3D 掃描結果

所有這些資料僅儲存在您的裝置本地儲存中（SwiftData 資料庫和檔案系統）。

#### 1.2 自動收集的資訊

我們**不**收集以下任何資訊：
- 裝置識別碼（UDID、IDFA、IDFV）
- IP 位址
- 使用分析或遙測資料
- 崩潰報告
- 位置資料
- 聯絡資訊
- 瀏覽歷史
- 任何其他個人資料

#### 1.3 無帳號系統

本 App **不**要求註冊、建立帳號或登入。沒有任何使用者檔案、密碼或帳號管理系統。

---

### 2. 我們如何使用您的資訊

由於我們不向自己的伺服器收集任何資料，唯一的處理行為是：

- **本地處理**：題目分析、遊戲生成、思維導圖建立——均由您配置的 AI 服務執行，資料從您的裝置直接傳送至您選擇的 AI 提供商
- **裝置端儲存**：將您的題目、筆記和設定儲存到裝置本地儲存，方便後續存取

我們不會將您的資料用於訓練、廣告、分析或任何其他目的。

---

### 3. 相機與相簿存取權限

本 App 請求存取您的相機和相簿，僅用於拍攝或匯入題目圖片：

| 權限 | 用途 | 是否必要？ |
|------|------|-----------|
| **相機** | 拍攝作業、試卷、教材頁面或 AR 掃描物體 | 是，用於相機功能 |
| **相簿（讀取）** | 從相簿匯入已有圖片 | 是，用於相簿匯入 |
| **相簿（寫入）** | 將匯出的思維導圖 PNG 儲存到相簿 | 可選 |

這些權限僅在**您首次使用對應功能時**請求。您可以隨時在裝置的 **設定** → **隱私權** 中管理或撤銷這些權限。

除您在本 App 內明確觸發的操作外，我們不會以任何其他目的存取您的相機或相簿。

---

### 4. AI 服務提供商

當您觸發 AI 分析功能時，題目文字和/或圖片會從您的裝置直接傳送至您在 App 設定中配置的第三方 AI 服務提供商。這僅在**您明確發起 AI 操作時**發生。

**重要說明：**

- 您需要為您選擇的 AI 提供商提供自己的 API 金鑰。本 App 不提供 AI 模型額度。
- 您配置的 AI 提供商（OpenAI、DeepSeek、Google Gemini、Claude 等）有自己的隱私權政策，管轄他們如何處理傳送至其服務的資料。
- 我們建議您查閱所選 AI 提供商的隱私權政策，了解其資料處理實務。
- 如果您使用本地 AI 模型（Ollama、LM Studio、llama.cpp），則沒有任何資料離開您的裝置。
- 本 App 無法存取您儲存在設定中的 API 金鑰——它們僅保存在您的裝置本地。

**支援的 AI 提供商列表**（均按其自身隱私權政策營運）：
- OpenAI
- DeepSeek
- Google Gemini
- Anthropic (Claude)
- 阿里雲（通義千問）
- 字節跳動（豆包）
- 智譜清言
- GitHub Copilot
- Ollama（本地）
- LM Studio（本地）
- llama.cpp（本地）

---

### 5. 第三方服務

本 App 使用以下內嵌在 App 套件中的第三方軟體元件（不會向其伺服器發送任何資料）：

| 元件 | 用途 | 發送的資料 |
|------|------|-----------|
| [marked.js](https://github.com/markedjs/marked) | Markdown 渲染 | 無（僅本地） |
| [KaTeX](https://github.com/KaTeX/KaTeX) | 數學公式渲染 | 無（僅本地） |
| [Mermaid](https://github.com/mermaid-js/mermaid) | 圖表渲染 | 無（僅本地） |

所有元件均包含在 App 套件本地——不會向其伺服器發起任何網路請求。

---

### 6. 資料儲存與安全

- **所有資料均儲存在本地**：使用 SwiftData（本地資料庫）和 App 沙箱檔案系統
- **加密備份**：當您選擇建立備份時，資料使用 AES-256-GCM 加密，並可選設定密碼
- **無雲端同步**：本 App 不會將資料同步到任何雲端服務
- **資料刪除**：卸載本 App 會刪除所有本地儲存的資料。您也可以透過 App 內的 **設定** → **快取管理** 清除資料

---

### 7. 兒童隱私

本 App 面向各年齡段的學生和學習者設計。由於我們不收集任何個人資訊，因此不存在無意中收集兒童資料的風險。本 App 不包含任何年齡限制內容。

---

### 8. 資料刪除

由於所有資料均儲存在您的裝置本地，您可以隨時透過以下方式刪除資料：

1. 在 App 內刪除單個項目（題目、筆記、掃描等）
2. 在 **設定** → **快取管理** 中清除快取
3. 從裝置卸載本 App

---

### 9. 本隱私權政策的變更

我們可能會不時更新本隱私權政策。更新時，我們會修改本政策頂部的「最後更新」日期。我們建議您定期審閱本政策。

---

### 10. 聯絡我們

如果您對本隱私權政策或您的資料有任何問題、疑慮或請求，請透過以下方式聯絡我們：

- **電子郵件**：[rollornot.app@icloud.com](mailto:rollornot.app@icloud.com)
- **回覆時間**：我們通常會在 24–48 個工作小時內回覆
