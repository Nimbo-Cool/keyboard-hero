# 鍵盤勇者 RPG｜離線版（GitHub Pages）

整個遊戲就是一個 `index.html`，不用伺服器、不用帳號。
進度存在「那台電腦的瀏覽器」裡；換電腦或電腦被還原時，用「🔑 通關密碼」接回進度。

## 放上 GitHub Pages（約 5 分鐘）
1. 登入 GitHub → 右上角 **＋ → New repository**，名稱例如 `keyboard-hero`，選 **Public** → Create。
2. 在新的 repository 頁面按 **uploading an existing file**，把這個資料夾裡的 `index.html` 拖進去 → **Commit changes**。
3. 到 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 **main**、資料夾 **/(root)** → Save。
4. 等 1～2 分鐘，網址會是：`https://你的帳號.github.io/keyboard-hero/`

## 之後要更新（一鍵）
雙擊 `一鍵部署_GitHub.bat`：
- 第一次會請你貼上 repository 網址（例如 `https://github.com/你的帳號/keyboard-hero`），並跳出視窗登入 GitHub。
- 之後每次換新的 `index.html`，再雙擊一次就會自動上傳，1～2 分鐘後生效。
- 電腦要先裝 Git（https://git-scm.com/download/win，一路按 Next）。

不想裝 Git 的話，也可以手動：回到 repository 上傳新的 `index.html`（同檔名會直接覆蓋）→ Commit。
學生的進度存在各自的瀏覽器，更新遊戲**不會**洗掉進度。

## 老師專區
- 標題畫面最下面「👩‍🏫 老師專區」，密碼預設 `1234`
  （要改的話：用記事本打開 `index.html`，搜尋 `TEACHER_PIN = '1234'` 改掉）
- 可以：貼上全班的通關密碼整理成表格／CSV、用示範帳號跳到任何任務、管理或刪除「這台電腦」的勇者資料。

## 升年級
等級、金幣、武器每學期重新開始；建立新學期角色時，填「上學期的通關密碼」可以拿傳承獎勵（金幣、藥水、稱號），打字最佳紀錄也會帶過來。

## 不想上網也可以
直接把 `index.html` 複製到每台電腦，雙擊用瀏覽器打開就能玩。
