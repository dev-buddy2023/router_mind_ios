# Privacy Policy / 隐私政策

**Last updated: June 11, 2026**

---

## English

### 1. Introduction
This Privacy Policy describes how RouterMind ("we", "our", or "the app") handles your information when you use our iOS application. RouterMind is designed with privacy as a core principle — all sensitive data stays on your device.

By using RouterMind, you agree to the practices described in this policy.

### 2. Information We Collect and How We Use It

#### 2.1 Voice Input
- **What**: When you use the voice input feature, your spoken words are captured as audio.
- **Processing**: Audio is transcribed to text **entirely on your device** using iOS Speech Recognition framework. The raw audio is never recorded, stored, or transmitted off your device.
- **Usage**: The resulting transcribed text is sent to OpenRouter API solely to generate model recommendations based on your natural-language request.
- **Retention**: Transcribed text is not stored by RouterMind. Each session is ephemeral — once the recommendation is delivered, the text is discarded.

#### 2.2 OpenRouter API Key
- **What**: Your OpenRouter API key, which you enter manually in the settings screen.
- **Storage**: Stored securely in the **iOS Keychain** (hardware-backed encryption). It never leaves your device except when making authorized requests to the OpenRouter API.
- **Usage**: Used exclusively to authenticate API calls to OpenRouter for model list retrieval and selection requests.
- **Control**: You can delete your API key at any time through the app settings. No backup is kept by us.

#### 2.3 Model Data
- **What**: Information about available LLM models (names, capabilities, pricing, context windows, etc.).
- **Source**: Loaded from a bundled local JSON file shipped with the app, and periodically refreshed from OpenRouter's public API.
- **Personal Data**: These requests contain your API key (for authentication) but **no personal information** such as name, email, device ID, or location.

#### 2.4 Favorites (Bookmarks)
- **What**: Models you mark as favorites for quick access.
- **Storage**: Stored **locally** in `UserDefaults` on your device.
- **Syncing**: Favorites are **not** synced to any cloud service or our servers. They stay on your device only.

#### 2.5 Language Preference
- **What**: Your language selection (Chinese or English).
- **Storage**: Stored **locally** in `UserDefaults` on your device.

### 3. Third-Party Services
RouterMind communicates with one external service:

| Service | Purpose | Data Sent |
|:--|:--|:--|
| **OpenRouter API** (openrouter.ai) | Model list retrieval, model selection requests, recommendation generation | API key + transcribed text of your request |

- OpenRouter's own privacy policy applies to data processed on their servers: [https://openrouter.ai/privacy](https://openrouter.ai/privacy)
- We encourage you to review their policy.

### 4. No Tracking, No Analytics, No Ads
- **No analytics SDKs** — we do not use Google Analytics, Firebase, Amplitude, or any similar service.
- **No crash reporting** — we do not use Crashlytics, Sentry, or any crash reporting tool.
- **No advertising** — there are no ads in the app and no ad-related SDKs.
- **No third-party trackers** — we do not embed any tracking pixels, fingerprinting scripts, or behavioral profiling tools.

### 5. Data Security
- **API Key**: Stored in iOS Keychain with hardware-backed AES-256 encryption.
- **Local storage**: UserDefaults is sandboxed per app; no other app can access it.
- **Network**: All communication with OpenRouter API is over HTTPS/TLS 1.3.
- **No backend**: RouterMind has no server infrastructure — there is no database, no cloud storage, and no backend service operated by us.

### 6. Children's Privacy
RouterMind is **not directed at children under the age of 13** (or the applicable age of consent in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided us with personal data, contact us immediately and we will take steps to delete such information.

### 7. Changes to This Privacy Policy
We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last updated" date. Material changes will also be communicated through the app.

### 8. Your Rights (GDPR / CCPA / Other Jurisdictions)
Since RouterMind does not collect or store personal data on any server:
- **Right to Access / Deletion**: There is no server-side data to access or delete. You can manage all local data (API Key, favorites, settings) directly within the app.
- **Right to Object**: You can stop using the app at any time. No ongoing data processing occurs after you close the app.
- **Data Portability**: All your data (favorites, settings) is already under your control on your device.

### 9. Contact
If you have any questions about this Privacy Policy, please contact:

**Email**: dev_buddy2023@163.com

---

## 中文

### 1. 引言
本隐私政策说明了 RouterMind（"我们"或"本应用"）在使用 iOS 应用时如何处理您的信息。RouterMind 以隐私为核心设计原则——所有敏感数据均存储在您的设备上。

使用 RouterMind 即表示您同意本政策所述的做法。

### 2. 我们收集的信息及使用方式

#### 2.1 语音输入
- **内容**：使用语音输入功能时，您的话语以音频形式被捕获。
- **处理方式**：音频**完全在设备本地**通过 iOS 语音识别框架转写成文字。原始音频不会被记录、存储或传输到您的设备之外。
- **用途**：转写后的文字仅发送给 OpenRouter API，用于根据自然语言请求生成模型推荐。
- **保留期限**：RouterMind 不存储转写文本。每个会话都是临时的——推荐结果生成后文本即被丢弃。

#### 2.2 OpenRouter API Key
- **内容**：您在设置页面手动输入的 OpenRouter API 密钥。
- **存储方式**：安全存储在 **iOS Keychain** 中（硬件级加密）。仅在向 OpenRouter API 发起授权请求时才会离开您的设备。
- **用途**：仅用于验证对 OpenRouter API 的调用，以获取模型列表和处理选择请求。
- **控制权**：您可以随时在应用设置中删除 API Key。我们不保留任何备份。

#### 2.3 模型数据
- **内容**：可用 LLM 模型的信息（名称、能力、价格、上下文窗口等��。
- **来源**：从应用自带的本地 JSON 文件加载，并定期从 OpenRouter 公开 API 刷新。
- **个人信息**：这些请求包含您的 API Key（用于认证），但**不包含任何个人信息**，如姓名、邮箱、设备ID或位置。

#### 2.4 收藏（书签）
- **内容**：您标记为收藏以便快速访问的模型。
- **存储方式**：**本地存储**在设备的 `UserDefaults` 中。
- **同步**：收藏**不会**同步到任何云服务或我们的服务器，仅保留在您的设备上。

#### 2.5 语言偏好
- **内容**：您选择的语言（中文或英文）。
- **存储方式**：**本地存储**在设备的 `UserDefaults` 中。

### 3. 第三方服务
RouterMind 与以下一个外部服务通信：

| 服务 | 用途 | 发送的数据 |
|:--|:--|:--|
| **OpenRouter API** (openrouter.ai) | 获取模型列表、处理模型选择请求、生成推荐 | API Key + 您请求的转写文字 |

- OpenRouter 自身的隐私政策适用于其在服务器上处理的数据：https://openrouter.ai/privacy
- 建议您查看该政策。

### 4. 无追踪、无分析、无广告
- **无分析 SDK**——我们不使用 Google Analytics、Firebase、Amplitude 或任何类似服务。
- **无崩溃报告**——我们不使用 Crashlytics、Sentry 或任何崩溃报告工具。
- **无广告**——应用内无广告，也不含广告相关 SDK。
- **无第三方追踪器**——我们不嵌入任何追踪像素、指纹脚本或行为分析工具。

### 5. 数据安全
- **API Key**：存储在 iOS Keychain，采用硬件级 AES-256 加密。
- **本地存储**：UserDefaults 按应用沙盒隔离，其他应用无法访问。
- **网络**：与 OpenRouter API 的所有通信均通过 HTTPS/TLS 1.3。
- **无后端**：RouterMind **没有服务器基础设施**——我们运营的没有数据库、没有云存储、没有后端服务。

### 6. 儿童隐私
RouterMind **不面向 13 岁以下儿童**（或您所在司法管辖区的适用同意年龄）。我们不会故意收集儿童的个人信息。如果您认为有儿童向我们提供了个人数据，请立即联系我们，我们将采取措施删除此类信息。

### 7. 隐私政策的变更
我们可能会不时更新本隐私政策。变更将通过此页面发布，并更新"最后更新"日期。重大变更也会通过应用内通知告知。

### 8. 您的权利（GDPR / CCPA / 其他司法管辖区）
由于 RouterMind 不在任何服务器上收集或存储个人数据：
- **访问/删除权**：没有服务器端数据需要访问或删除。您可以在应用内直接管理所有本地数据（API Key、收藏、设置）。
- **反对权**：您可以随时停止使用本应用。关闭应用后不会继续处理任何数据。
- **数据可移植性**：您的所有数据（收藏、设置）已在您的设备上由您自行控制。

### 9. 联系方式
如对本隐私政策有任何疑问，请联系：

**邮箱**：dev_buddy2023@163.com
