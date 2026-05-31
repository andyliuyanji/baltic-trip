# 波羅的海三國10日旅行計劃

香港出發 — 愛沙尼亞 · 芬蘭 · 瑞典 互動旅行計劃網頁

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

## 行程摘要

| 日期 | 行程 |
|------|------|
| 8/28 (五) | ✈ AY100 香港→赫爾辛基 (夜機) |
| 8/29 (六) | ✈ 抵達赫爾辛基 → 🚢 渡輪直達塔林 · 老城初探 |
| 8/30 (日) | 🇪🇪 塔林全日深度遊 |
| 8/31 (一) | 🚢 塔林 → 赫爾辛基 |
| 9/1 (二) | 🇫🇮 赫爾辛基全日探索 (Day 1) |
| 9/2 (三) | 🇫🇮 赫爾辛基悠閒探索 (Day 2) |
| 9/3 (四) | 🇫🇮 赫爾辛基半日 + 🚢 過夜渡輪至斯德哥爾摩 |
| 9/4 (五) | 🇸🇪 斯德哥爾摩全日探索 (Day 1) |
| 9/5 (六) | 🇸🇪 斯德哥爾摩全日探索 (Day 2) → ✈ AY818 飛赫爾辛基轉機 |
| 9/6 (日) | ✈ AY99 赫爾辛基→香港 17:40 抵達 |

## 航班

- 去程：AY100 HKG→HEL 20:55→05:35+1 (A350)
- 回程：AY818 ARN→HEL 21:10→22:20 (A321) + AY99 HEL→HKG 00:35→17:40 (A350)

## 功能特性

- Leaflet.js 互動地圖，18 個編號標記點，三國分色顯示
- 飛行/渡輪路線連線 (無自駕，全程公共交通)
- 10 天詳細日程表，含具體航班號 (AY100, AY818, AY99)
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
- Finnair / Tallink Silja / Turkish Airlines 官網 (航班資料)
