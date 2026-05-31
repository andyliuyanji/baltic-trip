# 波羅的海四國10日自駕旅行計劃

香港出發 — 瑞典 · 芬蘭 · 愛沙尼亞 · 拉脫維亞 互動旅行計劃網頁

## 線上版本

- **桌面版**：https://andyliuyanji.github.io/baltic-trip/
- **手機版**：https://andyliuyanji.github.io/baltic-trip/index-mobile.html

## GitHub 倉庫

https://github.com/andyliuyanji/baltic-trip

### 如何更新

```bash
cd /Users/andyliu/Documents/Claude/baltic-trip
git add . && git commit -m "更新內容" && git push
```

推送後 GitHub Pages 會在 1-2 分鐘內自動部署。

## 本地文件結構

```
baltic-trip/
├── index.html          # 桌面版 (側邊欄地圖 + 日程表)
├── index-mobile.html   # 手機版 (地圖上半 + 底部滑動面板)
├── images/             # 景點圖片 (18張，從 Wikimedia Commons 下載)
│   ├── gamla_stan.jpg
│   ├── helsinki_cathedral.jpg
│   ├── tallinn_old_town.jpg
│   ├── riga_old_town.jpg
│   └── ...
└── README.md
```

## 功能特性

- Leaflet.js 互動地圖，25 個編號標記點，四國分色顯示
- 飛行/渡輪/自駕三色路線連線
- 10 天詳細日程表，含具體航班號 (AY100, AY803, BT307, AY99)
- 點擊行程卡片 → 地圖聚焦當天景點
- 點擊景點名稱 → 地圖平移 + 自動彈出資訊視窗
- 彈出視窗含景點圖片 + Wikipedia 詳細介紹連結
- 手機版：全螢幕分割式設計，地圖上半 + 底部可滑動面板

## 資訊來源

- Rick Steves Travel Forum
- lovetravellingblog.com
- theblogtrotter.com
- day-trips-from.com
- Wikivoyage / Wikipedia
- Finnair / airBaltic / Turkish Airlines 官網 (航班資料)
