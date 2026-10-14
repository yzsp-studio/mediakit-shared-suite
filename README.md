<div align="center">

# 🎬 mediakit-shared-suite

## 15 个技能一条流水线：出图、出片、做应用，交付前先验片
## 15 skills, one pipeline: build apps, images, videos, verified before delivery

> ⚠️ **这是一套配合使用的技能组合（15 个）** —— 正文互相引用，建议成套取用。

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

由 15 个技能组成的创作与工程工具集，覆盖应用开发、视觉设计、视频生成与媒体处理四条主线。app-builder 面向全栈应用的设计、开发、排错与发布，creative-design、html、ppt 分别负责创意图片、独立 HTML 页面和幻灯片。creative-video 处理广告、宣传片、UGC 等通用视频，creative-drama 处理角色驱动的短剧、微电影、动画短片与长篇剧本，seedance-25 与 seedream-50 把视频、图片生成锁定到指定模型。mediakit 系列（shared/audio/editing/image/video）承担音视频与图像的裁剪拼接、转码封装、人声分离、内容理解与画质治理。artifact-preview 与 verifier-hub 在交付前把产物渲染成截图预览，并做格式、结构、数值层面的确定性校验，整套技能本来就是配合使用的：出图交设计、出片交视频、成片清理交 mediakit、交付前统一过预览与校验。

> ⚠️ **这是一套配合使用的技能组合（15 个）** —— 正文互相引用，建议成套取用。

### ✨ 能做什么

- app-builder：从 PRD、文档、截图或素材出发开发应用，支持加功能、改页面、修 Bug、分析源码、排查运行错误与查询发布状态
- creative-design / html：出海报、KV、Banner、封面、电商主图、Logo、信息图与知识科普图，也做分图层 HTML/CSS 视觉设计与独立页面
- creative-video / creative-drama：按需产出广告、宣传、UGC 视频，或走完短剧、微电影、动画短片的角色与剧情链路
- mediakit 五件套：音视频裁剪拼接、转码封装、人声背景分离、语音边界定位、抽帧与画面文字识别、图像压缩与增强
- artifact-preview：把 pdf/pptx/docx/xlsx/html/png 渲染成文字、页面截图、缩略图与多页拼接图，交付前肉眼自检
- verifier-hub：58 个子命令做文件格式、页数、章节、单元格、公式、关键词、占位符等交付前确定性校验

### 📦 包含的技能（配合使用）

- `app-builder` —— 见 [`app-builder/SKILL.md`](app-builder/SKILL.md)
- `artifact-preview` —— 见 [`artifact-preview/SKILL.md`](artifact-preview/SKILL.md)
- `creative-design` —— 见 [`creative-design/SKILL.md`](creative-design/SKILL.md)
- `creative-drama` —— 见 [`creative-drama/SKILL.md`](creative-drama/SKILL.md)
- `creative-video` —— 见 [`creative-video/SKILL.md`](creative-video/SKILL.md)
- `html` —— 见 [`html/SKILL.md`](html/SKILL.md)
- `mediakit-audio` —— 见 [`mediakit-audio/SKILL.md`](mediakit-audio/SKILL.md)
- `mediakit-editing` —— 见 [`mediakit-editing/SKILL.md`](mediakit-editing/SKILL.md)
- `mediakit-image` —— 见 [`mediakit-image/SKILL.md`](mediakit-image/SKILL.md)
- `mediakit-shared` —— 见 [`mediakit-shared/SKILL.md`](mediakit-shared/SKILL.md)
- `mediakit-video` —— 见 [`mediakit-video/SKILL.md`](mediakit-video/SKILL.md)
- `ppt` —— 见 [`ppt/SKILL.md`](ppt/SKILL.md)
- `seedance-25` —— 见 [`seedance-25/SKILL.md`](seedance-25/SKILL.md)
- `seedream-50` —— 见 [`seedream-50/SKILL.md`](seedream-50/SKILL.md)
- `verifier-hub` —— 见 [`verifier-hub/SKILL.md`](verifier-hub/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/mediakit-shared-suite.git
cp -r mediakit-shared-suite/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Fifteen skills covering four tracks: app engineering, visual design, video generation and media processing. app-builder designs, builds, debugs and ships full-stack apps, while creative-design, html and ppt produce creative imagery, standalone HTML pages and slide decks. creative-video handles ads, branded and UGC video, creative-drama handles character-driven short dramas, micro-films and animated shorts, and seedance-25 plus seedream-50 pin video and image generation to specific models. The mediakit family (shared/audio/editing/image/video) covers cutting, compositing, transcoding, vocal separation, content understanding and image/video quality governance. artifact-preview and verifier-hub render artifacts into screenshots and run deterministic format, structure and value checks before delivery, so the skills are meant to be chained rather than used in isolation.

> ⚠️ **A cooperating suite of 15 skills** — they reference each other; use them as a group.

### ✨ What it does

- app-builder: build apps from a PRD, docs, screenshots or assets, and add features, edit pages, fix bugs, read source and check release status
- creative-design / html: posters, key visuals, banners, covers, e-commerce hero shots, logos, infographics, plus layered HTML/CSS visual design and standalone pages
- creative-video / creative-drama: general ads, branded and UGC video, or the full character-and-plot chain for short dramas, micro-films and animated shorts
- mediakit family: cut, join, transcode, mux, separate vocals from background, detect speech boundaries, extract frames, OCR on screen and compress or enhance images
- artifact-preview: render pdf/pptx/docx/xlsx/html/png into text, page screenshots, thumbnails and multi-page collages for visual self-check before delivery
- verifier-hub: 58 subcommands for deterministic pre-delivery checks on format, page and section counts, cell values, formulas, keywords and placeholders

### 📦 Skills included (designed to work together)

- `app-builder` — [`app-builder/SKILL.md`](app-builder/SKILL.md)
- `artifact-preview` — [`artifact-preview/SKILL.md`](artifact-preview/SKILL.md)
- `creative-design` — [`creative-design/SKILL.md`](creative-design/SKILL.md)
- `creative-drama` — [`creative-drama/SKILL.md`](creative-drama/SKILL.md)
- `creative-video` — [`creative-video/SKILL.md`](creative-video/SKILL.md)
- `html` — [`html/SKILL.md`](html/SKILL.md)
- `mediakit-audio` — [`mediakit-audio/SKILL.md`](mediakit-audio/SKILL.md)
- `mediakit-editing` — [`mediakit-editing/SKILL.md`](mediakit-editing/SKILL.md)
- `mediakit-image` — [`mediakit-image/SKILL.md`](mediakit-image/SKILL.md)
- `mediakit-shared` — [`mediakit-shared/SKILL.md`](mediakit-shared/SKILL.md)
- `mediakit-video` — [`mediakit-video/SKILL.md`](mediakit-video/SKILL.md)
- `ppt` — [`ppt/SKILL.md`](ppt/SKILL.md)
- `seedance-25` — [`seedance-25/SKILL.md`](seedance-25/SKILL.md)
- `seedream-50` — [`seedream-50/SKILL.md`](seedream-50/SKILL.md)
- `verifier-hub` — [`verifier-hub/SKILL.md`](verifier-hub/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/mediakit-shared-suite.git
cp -r mediakit-shared-suite/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
