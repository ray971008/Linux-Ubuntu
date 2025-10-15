# 進入你的專案資料夾
cd {輸入檔案路徑}

# 建立虛擬環境
python -m venv env

# 啟動虛擬環境(啟動後會看到 (env) 標記)
(CMD)
.\env\Scripts\activate.bat

(vscode使用)
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass 
.\env\Scripts\Activate.ps1 

# 安裝套件
pip install {輸入套件}

# 執行程式
python {輸入檔案名稱}

# 關閉虛擬環境
deactivate
