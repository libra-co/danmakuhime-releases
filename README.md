<p align="center">
  <img src="icon.png" alt="DanmakuHime" width="128" height="128">
</p>

<h1 align="center">弹幕姬 DanmakuHime</h1>

<p align="center">
  为 macOS 打造的直播弹幕客户端
</p>

<p align="center">
  <a href="https://github.com/libra-co/danmakuhime-releases/releases"><img src="https://img.shields.io/github/v/release/libra-co/danmakuhime-releases?style=flat-square&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC" alt="Release"></a>
  <a href="https://github.com/libra-co/danmakuhime-releases/releases"><img src="https://img.shields.io/github/downloads/libra-co/danmakuhime-releases/total?style=flat-square&label=%E4%B8%8B%E8%BD%BD%E9%87%8F" alt="Downloads"></a>
</p>

---

## 截图

<p align="center">
  <img src="screenshot.webp" alt="DanmakuHime 截图" width="800">
</p>

---

## 功能

**实时弹幕** — 毫秒级延迟接收弹幕、礼物、SC 等互动消息，不错过直播间的每一条互动。

**弹幕过滤** — 灵活的过滤规则，屏蔽刷屏和无关消息，让你只看到真正重要的观众互动。

**语音播报** — 自动朗读弹幕和礼物信息，即使在游戏中也不会错过观众的每一条互动。

**OBS 联动** — 根据直播状态自动切换画面场景，智能控制推流内容，解放你的双手。

**虚拟形象联动** — 触发模型表情和动作，让你的虚拟形象与观众实时互动。

**插件扩展** — 丰富的插件生态，按需启用，自由组合，打造属于你的直播工作流。

**轻量流畅** — 极低内存占用，秒速启动，安静运行不打扰你的直播。

**深色 / 浅色主题** — 跟随系统自动切换，或手动选择你喜欢的外观。

---

## 下载安装

前往 [Releases](https://github.com/libra-co/danmakuhime-releases/releases) 页面下载最新的 `.dmg` 安装包。

支持 **macOS 10.15+**，同时提供 Apple Silicon（M 系列芯片）和 Intel 两个版本。

### 首次打开

由于未进行 Apple 代码签名，首次打开时 macOS 可能会提示"无法验证开发者"。请按以下步骤操作：

1. 打开 **系统设置 → 隐私与安全性**
2. 在页面底部找到关于 DanmakuHime 的提示
3. 点击 **"仍要打开"**

之后即可正常使用。

---

## 最近更新

<!-- CHANGELOG_START -->
### v0.2.0 · 2026-07-25

### ✨ 新功能

- **一键开播**：无需再打开网页后台，在软件内选择分区即可开播，推流地址与密钥自动生成，复制到 OBS 即可直播。若所选分区需要实名认证，将直接提供认证入口。
- **断网自动补弹幕**：直播中网络中断时，中断期间的弹幕、礼物与醒目留言会在重连后自动补回列表与数据统计，避免遗漏互动。
- **语音播报优化**：支持设置播报的优先顺序（如礼物、观众发言优先）；高人气直播间不再被「欢迎进入直播间」刷屏；播报音量可单独调节。
- **OBS 弹幕样式**：内置深色、透明描边、浅色三套预设样式，同时支持自定义样式。
- **悬浮窗发送弹幕**：弹幕悬浮窗底部新增输入框，可在不切回主界面的情况下回复观众。
- **刷屏弹幕折叠**：连续重复的弹幕自动合并为一条并显示数量，同时支持按自定义规则屏蔽指定弹幕。
- **屏蔽词管理**：可在软件内直接维护直播间屏蔽词，命中弹幕自动拦截。
- **防录屏窗口**：弹幕窗口可在录屏、截图与推流采集中隐藏，便于录制教程或二次剪辑。

### 🛠 优化与修复

- 禁言时长调整为按小时设置，控场更精细。
- 适配 B站 新版的进场、关注与高能榜消息，相关互动可正常显示。
- 修复部分 B站 表情（尤其付费大表情）在弹幕中显示为空白的问题。
- 修复网络波动后弹幕列表与数据统计被清空的问题，重连后数据得以保留。
- 修复醒目留言（SC）与大航海开通有时不弹出、不计入列表的问题。
- 提升开播与断线重连的稳定性。

---

### v0.1.2 · 2026-03-29

- 更新应用图标
- 修复更新提示中显示的版本号错误
- 修复个别界面出现多余的「0」

---

### v0.1.1 · 2026-03-23

- 减小安装包体积
- 修复若干界面显示细节

---
<!-- CHANGELOG_END -->

查看完整更新日志：[CHANGELOG.md](CHANGELOG.md)

---

## 关于作者

**Libra** — B站主播 & 独立开发者

- B站：[@原来是Li哇](https://space.bilibili.com/26190537)
- 直播间：[live.bilibili.com/4536023](https://live.bilibili.com/4536023)
- 官网：[danmakuhime-8qjbmg8b.manus.space](https://danmakuhime-8qjbmg8b.manus.space)

---

## 反馈与建议

如果你在使用中遇到问题或有功能建议，欢迎通过以下方式联系：

- 在 [Issues](https://github.com/libra-co/danmakuhime-releases/issues) 中提交反馈
- 到 [直播间](https://live.bilibili.com/4536023) 直接告诉我
