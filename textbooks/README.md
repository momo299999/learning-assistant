# 教材存放目录

请将你要学习的教材文件放在此目录下。

## 支持的格式
- **Markdown (.md)** — 推荐格式，AI 可以直接读取
- **纯文本 (.txt)** — 可直接读取
- **EPUB (.epub)** — 可用 Pandoc 转为 Markdown 后使用
- **MOBI (.mobi)** — 可用 Pandoc 转为 Markdown 后使用
- **PDF (.pdf)** — 可读取，但建议转为 markdown 以获得最佳效果

## 教材准备建议

### 最佳实践
1. 将教材按章节拆分为独立文件（如 `ch01_引言.md`, `ch02_基础概念.md`）
2. 文件名包含章节编号，便于排序
3. 每个文件开头注明章节标题

### 格式转换
如果教材是 PDF/EPUB/MOBI 格式，建议先转换为 Markdown：
- **EPUB/MOBI → Markdown**：使用 Pandoc（`pandoc book.epub -o book.md`）
- **PDF → Markdown**：使用 Marker（`pip install marker-pdf`）或 Pandoc
- 转换后按章节拆分，每章一个文件

### 注意事项
- 教材文件为只读，系统不会修改此目录下的内容
- 可以放入多本教材，在课程大纲中指定当前学习的教材
- 教材内容仅用于本地教学，不会上传到任何服务器
