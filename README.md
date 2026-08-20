# 句译 · 中译英翻译写作练习工具
**JuYi-ZH-EN-Sentence-Practice**

[在 GitHub Pages 中在线使用](https://liumashiro.github.io/JuYi-ZH-EN-Sentence-Practice/JuYi.html)

---

句译是一个专为英语学习者设计的单页应用。

以“单句拆分，专注输出”为设计原则，从单句开始写作。

只需粘贴一段中文原文，程序会自动将其拆分为单句，以逐句进行英文翻译写作练习。遇到生词随时调用内置词典，最终将写好的句子一键复制交给 AI 进行批改优化。

<img width="2738" height="1441" alt="image" src="https://github.com/user-attachments/assets/ad1c6888-5e70-46b9-93d4-1b0047d94452" />



## 快速开始
- 下载 .html 文件，双击打开即可运行
- 输入中文段落，拆句，翻译
- 将逐句翻译结果或整篇翻译结果复制，交由 AI 进行批改优化。
- 进阶（可选）使用Chrome app式窗口打开（独立窗口而非标签页，UI更清爽，使用更方便）：
  - 在桌面右键添加快捷方式，输入`"C:\Program Files\Google\Chrome\Application\chrome.exe" --app=file:///{html位置}` ，如`"C:\Program Files\Google\Chrome\Application\chrome.exe" --app=file:///C:/Users/{Username}/Documents/JuYi.html`

## 功能
- 智能分句：自动按标点符号将中文原文拆分为单句列表。
- 逐句处理：逐句翻译，逐句校对，逐句保存。
- 划词查词：选中生词，自动弹出浮标，点击即可查阅译法。
- 错误标红：在写好的英文译文中，选中特定词组或语法错误进行“标红”，方便日后复盘。若有缺词，还可以添加缺词标记。
- 版本管理：支持逐句或整篇保存初稿、二稿与终稿，随时查看历史版本、只读预览或一键恢复。
- 数据备份：一键导出全量 JSON 备份文件，支持随时导入恢复。
- 数据完全本地存储。

## 说明
  - 使用查词典功能时，可能调用[MyMemory 机器翻译](https://mymemory.translated.net/)、[Free Dictionary API](https://www.FreeDictionaryAPI.com)（源自[Wiktionary](https://en.wiktionary.org/)）提供查词服务。
