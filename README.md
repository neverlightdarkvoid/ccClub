# 台灣登山資訊整合查詢面板（ccClub 2024 Spring 專案）

## 專案簡介
本專案旨在整合台灣登山所需的各類資訊，包括登山路線、住宿、交通、餐食與天氣資料。透過 Python 爬取不同網站的公開資料，並彙整至雲端資料庫，最終以 Tableau Public 製作互動式查詢面板，提升登山者搜尋資訊的效率與便利性。

## 動機
現有的登山資訊分散於多個網站，使用者需耗費大量時間比對各種資料。本專案希望透過資料整合與視覺化展示，讓使用者能在一個面板上快速查詢所有必要資訊，提升規劃行程的效率與體驗。

## 開發流程
- 蒐集並篩選登山資訊相關網站
- 使用 Python 撰寫爬蟲，進行資料擷取與清理
- 規劃資料庫結構，部署至雲端
- 設計 Tableau Public 儀表板，整合視覺化介面

## 使用技術
- **語言與框架**：Python、爬蟲套件（requests、BeautifulSoup）
- **資料視覺化**：Tableau Public
- **資料儲存**：雲端資料庫（Google sheet）
- **版本控制**：Git

## 資料來源
- [行政院登山資訊網站](https://www.ey.gov.tw/state/4447F4A951A1EC45/dc08391a-c57c-4cf7-af9a-cc0d9e4ebb1c)
- [健行筆記](https://hiking.biji.co/index.php?q=trail&act=gpx_list)
- [山岳協會](https://www.tmca-tpe.org/content.asp?id=676&cat=98&type=2)
- [法蘭怎麼玩-高山百岳資料整理](https://94frank.com/category/taiwan-outdoor-life/outdoor-tips/high-mountain-and-100-peaks-data-and-info/)

## 成員貢獻
- 資料蒐集與爬蟲開發
- 資料清理與雲端部署
- Tableau 儀表板設計與互動功能規劃
