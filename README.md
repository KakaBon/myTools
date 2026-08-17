# My Tools

这里整理的是我在实际使用过程中，为解决自己的需求而开发或逐步完善的一些工具。

很多工具最初都来自一个具体需求：先遇到问题，再把原本需要手工完成的流程逐渐做成脚本、桌面工具或自动化流程。

单个工具分别保存在独立仓库中；属于同一完整工作流程的工具，在这里按项目归类。

---

## Series OST Tracking

用于整理电视剧中出现的 OST、配乐及其出现位置，并将整理完成的工作簿导出为方便浏览的 HTML 版本。

### Series OST Tracker

**[Series-OST-Tracker-Template-Automated](https://github.com/KakaBon/Series-OST-Tracker-Template-Automated)**

基于 Excel 的电视剧 OST 追踪与整理工具，用于记录曲目、出现集数、时间点及相关信息，并自动维护曲目收录和使用统计。

### OST HTML Exporter

**[OST-HTML-Exporter](https://github.com/KakaBon/OST-HTML-Exporter)**

将完成后的 OST Excel 工作簿导出为适合直接在浏览器中查看和分享的 HTML 文件。

---

## QQ Music Batch Download Workflow

用于从已有歌曲列表生成下载任务，并通过 QQ 音乐网页完成批量匹配、播放、资源捕获、下载以及后续音频格式处理。

整个流程由几个相互独立的工具组成。

### 1. QQMusic Task List Builder

**[QQMusic-Task-List-Builder](https://github.com/KakaBon/QQMusic-Task-List-Builder)**

从已有歌曲文件生成批量处理所需的任务表，为后续自动化下载提供歌曲信息和搜索任务。

### 2. QQMusic Web Helper Automated

**[QQMusic-Web-Helper-Automated](https://github.com/KakaBon/QQMusic-Web-Helper-Automated)**

根据任务表自动执行 QQ 音乐网页搜索、结果匹配、播放、资源捕获和批量任务控制。

### 3. Format Tools

**[Format-Tools](https://github.com/KakaBon/Format-Tools)**

用于处理下载后的音频文件，包括格式检测、文件名清理以及 MP3 转换。

---

## Timeline Tools

用于制作和查看时间轴的工具。

### Desktop Timeline Tool

**[timelineMakerDesktop](https://github.com/KakaBon/timelineMakerDesktop)**

已实现基础桌面版本（MVP），用于时间轴内容的制作与编辑。

### Web Timeline Tool

**[timelineMakerSite](https://github.com/KakaBon/timelineMakerSite)**

已实现基础网页版本（MVP），用于在浏览器中查看时间轴。

---

## Read What You Want

用于对 TXT 文本进行批量替换和阅读过程中实时编辑的 Android 工具。

### rwyw_reader 阅你想阅阅读器

**[rwyw_reader](https://github.com/KakaBon/rwyw_reader)**

以文本替换和实时编辑为主要功能的 Android TXT 阅读器。支持通过自定义规则脚本批量修改一本或多本 TXT，也可以在阅读过程中直接编辑当前文本；同时提供基础的书架、章节、搜索和书签功能。
