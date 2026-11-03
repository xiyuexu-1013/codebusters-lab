# Codebusters 解码实验室

面向 Science Olympiad 2026–27 Division C 的中文互动学习网站，保留英文术语。提供 12 节分阶段课程、原创解码短题、逐步提示、自动判题、浏览器本地进度与 15 分钟混合练习。

## 运行

直接打开 `dist/index.html` 即可使用。若需要本地网页服务器，在此文件夹运行：

```bash
python3 -m http.server 8000 --directory dist
```

浏览器访问 `http://localhost:8000`。部署静态网站时，把 `dist/` 作为网站根目录即可。本站没有服务器依赖，进度保存在当前浏览器的 `localStorage`；换设备或清除浏览器数据后无法恢复。

## 规则说明

截至 2026-11-02，Science Olympiad 官方 2027 Division C 规则 PDF 由[官方规则页](https://www.soinc.org/rules-2027)的表单提供。本项目核对了[官方 Codebusters 活动页](https://www.soinc.org/codebusters-c)，并依据其链接的 Toebes 工具站所发布的[2026–27 题型汇总](https://ncc.toebes.com/codebusters/Rule-Summary-2027.html)整理课程范围。手册全文和后续[官方澄清、修订](https://www.soinc.org/events/submit-question-and-rule-clarifications)优先于本网站。各节短题为教学简化题，不声称复现正式试卷。

Caesar 是入门预备知识，未标成 2027 C 组正式题型。普通 Morse 作为 Fractionated Morse 的前置知识。题型汇总显示 2027 C 组包含 Aristocrat、Patristocrat、Xenocrypt、Baconian、Fractionated Morse、Porta、Homophonic、Nihilist Substitution、Checkerboard、Cryptarithm（十进制）和 Complete Columnar；不同赛事级别的要求可能不同。

## 视频来源

“视频与规则”页的链接来自 Science Olympiad 官方 Codebusters 页或 Toebes Codebusters 工具站。旧赛季讲座已标注年份，不能用于代替 2027 规则。
