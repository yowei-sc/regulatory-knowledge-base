# 資安法規與標準知識庫

這是一個以 MkDocs 建立的繁體中文靜態網站，用官方來源整理 CRA、產品資安標準與 O-RAN 安全規格。

## 本機執行

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m mkdocs serve
```

瀏覽器開啟 `http://127.0.0.1:8000/`。

## 建置檢查

```powershell
.\.venv\Scripts\python.exe -m mkdocs build --strict
```

## 內容維護

- 公開文章只放在 `docs/`。
- 新增文章時要填寫 Front Matter、附官方來源並更新 `mkdocs.yml`。
- 私有參考資料只放在已被 Git 忽略的 `source-material-private/`，不得複製到公開頁面。
- 完整開發規則請先閱讀 `AGENTS.md`；其他 AI 工具則由 `CLAUDE.md` 導入同一份規則。

## 發布

推送至 GitHub 的 `main` 分支後，`.github/workflows/deploy-pages.yml` 會建置網站並部署至 GitHub Pages。第一次發布前，仍需在 GitHub 儲存庫的 Pages 設定中選擇 **GitHub Actions** 作為來源。
