# 🎬 AI 视频作品集

<div align="center">

[![在线观看](https://img.shields.io/badge/在线观看-手机也能看-4f6df5?style=for-the-badge)](https://jin2004-cmd.github.io/ai-video-portfolio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)](LICENSE)
[![纯静态](https://img.shields.io/badge/站点-纯静态无构建-22c55e?style=for-the-badge)](#技术说明)

</div>

> 🟢 **在线观看（手机也能看）**：[jin2004-cmd.github.io/ai-video-portfolio](https://jin2004-cmd.github.io/ai-video-portfolio/)
>
> 里面还藏了一个我做的小应用：[`/offer-agent/` 秋招求职引擎](https://jin2004-cmd.github.io/ai-video-portfolio/offer-agent/)（[源码](offer-agent/index.html)，手机端可添加到主屏幕当 App 用）

我做着找工作用的 AI 视频作品集。网站是纯静态的（一个 `index.html` + `assets/` 里的视频图片，GitHub Pages 托管，没有构建工具），里面每条片子从画面到成片都是我一个人跑通的。

---

## 里面有什么

### 《候》— 27 秒 AI 短片（主打片）

给腾讯互娱 48 小时 AI 动画测试做的游戏 CG 风格短片。仙侠 + 都市，乌鸦跟飞开场，主角银白高马尾、黑风衣配青蓝云纹刺绣，结尾是眼部特写、瞳孔里倒映出恶魔剪影。

- 规格：1920×1080 / 30fps
- 全流程：**豆包 Seedream 文生图（三视图母版法锁角色一致性）→ Seedance 2.0 图生视频 → 剪映成片**（智能消除水印、闪白转场遮形态跳变、配乐卡点）
- 角色一致性是 AI 短片最难踩的坑，三视图母版是我自己摸出来的解法，面试可以现场复盘迭代过程

### 《悟空》— AI 短片练习

黑神话风格的镜头练习，验证同一套管线做写实题材行不行。

### 千川投流素材（5 条竖屏）

实习期间参与制作的抖音千川竖屏素材：产品露出、情景对白、卖点演示。这是**商业投放语境下的练习，不是自娱自乐的片子**——前三秒留人、卖点密度、口播节奏都是按投流逻辑剪的。

### 剪辑与动效练习

蒙版生长文字动画、歌词蒙版动效、多画面快切、短剧对白节奏（对应站点里的《GROWTH·生长》《ECHOES·回响》）。

---

## 技术说明

- 纯静态站点，无框架无构建，`index.html` 单文件 + 媒体资源
- 海报帧（poster）单独导出，移动端不自动加载视频，省流量
- 生产约束是真的：Seedance 免费额度每天 10 条 5 秒，生产计划是按这个约束排的——哪条镜头一次过、哪条废了几条，我都记得

## 实话实说

这些是学生作品，不是商业项目；部分练习片目前还是标清，我在陆续换成 1080p。练习片和成片放一起，是因为我觉得**只给看成片，看不出人是怎么一点点做对的**。

---

## English

**AI Video Portfolio** — a pure-static site (single `index.html` + media assets on GitHub Pages, no build step) showcasing AI-generated short films made end-to-end by one person. The feature piece "候 (Waiting)" is a 27-second game-CG-style short made for a 48-hour AI animation test: character consistency locked via a three-view master-sheet method with Seedream text-to-image, animated with Seedance image-to-video, finished in CapCut. Also includes a realistic-style practice film, five commercial short-ad verticals produced during an internship, and motion-design exercises. Poster frames are exported separately so mobile never auto-loads video.

👉 Watch online: <https://jin2004-cmd.github.io/ai-video-portfolio/>

---

<div align="center">

如果这条「三视图锁角色一致性」的管线对你有启发，欢迎 ⭐ **Star** 一下。

</div>
