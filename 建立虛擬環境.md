#1 打開終端機，進入專案資料夾
cd ~/{檔案夾路徑}

#2 建立虛擬環境
python3 -m venv myenv

#3 啟動虛擬環境
source myenv/bin/activate

#4 安裝專案需要的套件
pip install {套件:多個套件中間隔空白即可}

#5 執行程式
python3 {檔案.py}

#6 停用虛擬環境
deactivate
