# Learning

八门已完成课程的中文学习讲义与摘要，涵盖深度学习、计算机视觉、算法、批判性思维、哲学、博弈论和经济哲学。

仓库保存课程摘要、来源链接和文件校验清单；最终合订本保存在 [Releases](https://github.com/xianDE1234561/Learning/releases)，便于单独下载。此版本不含转写过程、原始视频与音轨、字幕、模型、临时缓存或历史草稿。

## 课程目录

| 课程与摘要 | 视频单元 | 合订本页数 | 最终版本 |
| --- | ---: | ---: | --- |
| [CS231N 2025 计算机视觉深度学习](cs231n-2025.md) | 18 | 613 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.25/CS231N-2025-final.pdf) |
| [MIT 6.S191 2026 深度学习导论](mit-6s191-2026.md) | 9 | 492 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.25/MIT-6S191-2026-final.pdf) |
| [MIT 6.006 Fall 2011 算法导论](mit-6006-2011.md) | 47 | 235 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.25/MIT-6006-2011-final.pdf) |
| [批判性思维大师课](critical-thinking.md) | 59 | 259 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.25/Critical-Thinking-final.pdf) |
| [Crash Course 哲学](crash-course-philosophy.md) | 47 | 259 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.25/Crash-Course-Philosophy-final.pdf) |
| [William Spaniel Game Theory 101 博弈论](game-theory-101.md) | 86 | 204 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.25/Game-Theory-101-final.pdf) |
| [苏黎世大学 2022 经济哲学](philosophy-of-economics.md) | 40 | 316 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.25/Philosophy-of-Economics-2022-final.pdf) |
| [深度学习专项五部分](ai-deep-learning-specialization.md) | 184 | 641 | [下载](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.28/AI-Deep-Learning-Specialization-final.pdf) |

MIT 6.006 的 47 个单元包含 24 节 Lecture 与 23 节 Recitation；Crash Course 的 47 个分 P 包含 1 个预览与 46 节正式课程。其他课程保留对应合集的分 P 范围。

本版八门课程合订本共 3,019 页。2026-10-28 新增 AI 深度学习专项五部分完整讲义：184 个源片段、641 页合订本。提示工程未纳入本次发布。

## 本次新增：AI 深度学习专项

[2026-10-28 Release](https://github.com/xianDE1234561/Learning/releases/tag/v2026.10.28) 提供 [641 页最终合订本](https://github.com/xianDE1234561/Learning/releases/download/v2026.10.28/AI-Deep-Learning-Specialization-final.pdf)。五部分来源、内容摘要和版本范围见 [课程摘要](ai-deep-learning-specialization.md)。

先前七门课程的附件继续保存在 [2026-10-25 Release](https://github.com/xianDE1234561/Learning/releases/tag/v2026.10.25)。

## 下载与校验

从上表或 Release 页面下载所需讲义。网页的 **Code → Download ZIP** 仅包含摘要与清单，PDF 须从 Release 附件下载。

[manifest.json](manifest.json) 记录文件大小、页数、来源与 SHA-256；[SHA256SUMS.txt](SHA256SUMS.txt) 可用于校验下载文件。例如在 PowerShell 中执行 `Get-FileHash .\CS231N-2025-final.pdf -Algorithm SHA256`，与清单对比。

## 来源与使用说明

这些文件是个人学习整理的中文讲义，包含课程内容梳理、推导、算例、自测与参考答案；整理者补充、材料限制与未运行实验以讲义和各课程摘要的说明为准。它们不是原机构、原作者发布的官方教材，也不宣称所有代码均已完成训练复现。

课程、视频、幻灯片、原文摘引及图像的权利属于各权利人。本仓库未对第三方材料授予统一开源许可；引用或再使用时请核对具体来源及其许可。

索引更新：2026-10-28。
