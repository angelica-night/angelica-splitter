# 白芷切分工具

把 DeepSeek 导出的 ZIP 对话记录，按 Token 切分成可导入的文本块。

## 功能

- 直接选择 DeepSeek 导出的 ZIP（不用解压）
- 显示每个会话的 Token 数、消息数
- 按设定的 Token 数切分（最低 10000，防止拆散单条消息）
- 支持「只取最近 N token」（快速续上，跳过早期设定）
- 一键下载（逐块 txt）

## 使用

**在线用（推荐）**：打开 https://angelica-night.github.io/angelica-splitter/ 直接用，不用下载。

**下载离线用**：下载 `index.html`，双击用浏览器打开（推荐 Chrome / Edge）。

操作：选 ZIP → 勾选会话 → 设 Token → 点「切分并导出」→ 下载得到多个 txt 块。

## 隐私

**本工具纯本地运行，数据不离开你的电脑。**
所有处理都在浏览器内存里完成，没有任何上传。
代码公开可查，你可以自己打开 HTML 看，不放心可以把代码丢给 AI 问。

## 关于

- 作者：白芷不熬夜（小红书）
- 用途：帮助养 OC 的用户把被锁的对话救出来
- 版本：v0.1

## 许可

MIT License，见 [LICENSE](LICENSE)。
