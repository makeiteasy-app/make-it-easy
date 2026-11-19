# 隐私政策 / Privacy Policy

最后更新：2026-11-16

**一句话：你的文献和数据都留在你自己的电脑上，我们收不到。**

## 我们不收集什么

Make It Easy 没有账号系统，不做使用统计、遥测或崩溃上报，也不会自动联网更新。我们（开发者）收不到你的文献、译文、高亮、提问、设置或任何使用记录。

## 数据存在哪里

- 文献库（原 PDF、编译结果、阅读页缓存、你的高亮和提问）和设置都存在你自己的电脑上，默认在 `%APPDATA%\Make It Easy`，可以在「存储位置」里搬到别的盘。
- 云端 API 的密钥只存在本机，系统支持时会加密保存。
- 卸载 App 不会自动删除文献库；不需要时可以手动删掉那个文件夹。

## App 会连接哪些地方

只有在你使用相应功能时才会连接：

| 连到哪里 | 什么时候 | 发送什么 |
|---|---|---|
| 你选择的 AI 服务商（OpenAI、Anthropic、Google、DeepSeek 或你填写的兼容接口） | 编译、生成演示、提问时 | 完成这件事需要的论文内容（页面图像或文字、相关段落）和你的问题 |
| 你电脑上的命令行助手（Claude Code、Codex、Antigravity CLI） | 选择「本机命令行」接入时 | 同上，由这些助手转发给它们各自的服务 |
| 本机桥接（127.0.0.1，不出你的电脑） | 使用本机命令行接入时 | App 内部转交任务 |
| npm、nodejs.org | 你点「安装命令行助手」时 | 下载安装这些工具 |

发给 AI 服务商的内容，按你和该服务商之间的条款处理（包括是否用于训练、保存多久）。请在接入前看一下所用服务商的隐私政策。

## 联系

对隐私有疑问，请在 [Issues](https://github.com/makeiteasy-app/make-it-easy/issues) 里留言。本政策有改动时，会更新这个页面和上面的日期。

---

## English

**In short: your documents and data stay on your computer; we never receive them.**

- Make It Easy has no accounts, no analytics, no telemetry, no crash reporting and no automatic updates. We (the developers) receive none of your documents, translations, highlights, questions, settings or usage.
- Your library (original PDFs, compiled results, highlights and questions) and settings are stored locally, by default in `%APPDATA%\Make It Easy`; you can move them under "Storage location". Cloud API keys are stored locally and encrypted when the system supports it.
- The app connects only when you use a feature: to the AI provider you chose (OpenAI, Anthropic, Google, DeepSeek or a compatible endpoint you entered), directly or through a command-line assistant on your computer (Claude Code, Codex, Antigravity CLI), sending the paper content and questions needed for that task; to a local bridge on 127.0.0.1 that never leaves your computer; and to npm / nodejs.org (or Google's official Antigravity installer) when you ask it to install a command-line assistant.
- What you send to an AI provider is governed by your terms with that provider. Please read its privacy policy before connecting.
- Questions: open an issue at https://github.com/makeiteasy-app/make-it-easy/issues.
