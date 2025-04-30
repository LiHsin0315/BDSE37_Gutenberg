# Project Gutenberg
爬取中文書籍，共 398 本。

## 安裝套件
- requests==2.32.3
- beautifulsoup4==4.13.4
- selenium==4.31.0

## 成果
...
[20250430_BDSE37_Gutenberg_作業影片](https://youtu.be/vtHmGmwyJk8))
...

## 其它你想要補充標題和內容
本專案會：
- 前往 Project Gutenberg 中文書籍目錄
- 過濾掉沒有中文書名或無法下載 `.txt.utf-8` 的書籍
- 抓取並儲存符合條件的純中文內容文字檔  
儲存路徑預設為 `project_gutenberg/` 資料夾中。
