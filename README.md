# 論文的資料分析部分
### 分析工具：倒傳遞類神經網路

主要使用 sklearn 套件實作 BPN 進行分類：

- BPN_Eye.ipynb : 單獨處理 眼動資料
- BPN_Mind.ipynb : 單獨處理 腦波資料
- BPN_All.ipynb : 一起處理 腦波資料及眼動資料

前處理部分：

- EyesToUtf8.ipynb : 解決眼動資料編碼問題
- Preview.ipynb : 單筆數據資料的顯示
- Process_all.ipynb : 資料的前處理，取特徵值