# 背单词 · 双栏 + 生词本

单文件背单词网页：导入词书（csv/xlsx/xls）→ 按日期看当天单词 → 双栏多选转移 → 生词本管理。
数据存在浏览器 IndexedDB，可导出/导入 JSON 备份。

## 使用
直接打开 `index.html`，或部署到任意静态托管。

## 词书格式
四列表头（大小写、中文都可）：`day, word, phonetic, meaning`
示例见 `Unit2生词.csv`。
