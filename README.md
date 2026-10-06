# 微信截图助手（WeChat Screenshot）

一个极小的 Windows 工具：运行后立即触发微信自带的截图功能（相当于按下 Alt + A）。

A tiny Windows utility: running it instantly triggers WeChat's built-in screenshot tool (equivalent to pressing Alt + A).

## 下载 | Download

前往 [Releases](https://github.com/jionghang/WeChatScreenshot/releases/latest) 页面下载最新的 `WeChat screenshot.exe`。

Get the latest `WeChat screenshot.exe` from the [Releases](https://github.com/jionghang/WeChatScreenshot/releases/latest) page. No installation required.

## 使用方法 | Usage

1. 确保微信已登录并运行，且截图快捷键为默认的 **Alt + A**。
2. 双击运行 `WeChat screenshot.exe`，微信截图界面随即出现。

---

1. Make sure WeChat is logged in and running, with the default screenshot hotkey **Alt + A**.
2. Double-click `WeChat screenshot.exe` and the WeChat screenshot overlay will appear.

## 使用技巧 | Tips

- **桌面快捷方式**：右键 `WeChat screenshot.exe` -「发送到」-「桌面快捷方式」，需要截图时双击桌面图标即可。
- **固定到任务栏**：右键 `WeChat screenshot.exe` 或其快捷方式 -「固定到任务栏」，之后单击任务栏图标就能开始截图。

- **Desktop shortcut**: Right-click `WeChat screenshot.exe` → "Send to" → "Desktop (create shortcut)", then double-click the desktop icon whenever you need a screenshot.
- **Pin to taskbar**: Right-click the exe or its shortcut → "Pin to taskbar" — one click on the taskbar icon starts a screenshot.
- **Bind to mouse side buttons / macro keyboards**: Many button-mapping tools (Logitech G HUB, Razer Synapse, Stream Deck, etc.) can only "launch a program" rather than "send a key combo". Point the button action at this exe to trigger WeChat screenshots with a single button press.

## 关于杀毒软件误报 | Antivirus False Positives

VBS 转 EXE 类工具生成的程序可能被杀毒软件误报（该类工具的通病）。如遇到，可将其加入杀毒软件白名单。完整源码见 [src/WeChatScreenshot.vbs](src/WeChatScreenshot.vbs)，可自行审查。

Programs compiled by VBS-to-EXE converters are often flagged by antivirus software (a common false positive for this class of tools). If that happens, add it to your antivirus whitelist. The full source is only 3 lines — see [src/WeChatScreenshot.vbs](src/WeChatScreenshot.vbs) — feel free to review it yourself.

## License

[MIT](LICENSE)
