# 待辦事項小助手

使用 Python Flask 實作，支援新增、刪除、完成、恢復與列出待辦事項。

## 啟動

```bash
pip install flask
python app.py
```

開啟 `http://127.0.0.1:5000`。

資料會儲存在專案根目錄的 `todos.json`。

## 專案結構

- `app.py`：Flask 主程式
- `templates/index.html`：HTML/CSS 頁面
- `todos.json`：待辦事項資料，第一次新增時自動建立
- `skills/`：專案使用的 AI skills
