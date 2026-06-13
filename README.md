# 波羅的海+奧地利13日旅行計劃

香港出發 — 愛沙尼亞 · 芬蘭 · 奧地利（自駕湖區+薩爾茨堡）13日互動旅行計劃網頁

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
├── images/             # 景點圖片
│   ├── tallinn_old_town.jpg
│   ├── helsinki_cathedral.jpg
│   └── ...
└── README.md
```

## 行程摘要

| 日期 | 行程 |
|------|------|
| 8/26 (三) | ✈ AY100 香港→赫爾辛基 (夜機) |
| 8/27 (四) | ✈ AY1011 HEL→TLL 07:00→07:40 抵達塔林 · 全日老城探索 |
| 8/28 (五) | 🇪🇪 塔林全日深度遊 Day 2 · 老城 · 博物館 |
| 8/29 (六) | 🚢 早上渡輪塔林→赫爾辛基 → 赫爾辛基精華半日 → ✈ AY1475 16:55→18:20 飛維也納 |
| 8/30 (日) | 🇦🇹 維也納 Day 1：美泉宮 · 美景宮 · 🚗 取車 |
| 8/31 (一) | 🇦🇹 維也納上午 → 🚗 自駕前往哈修塔特 (~3.5h) |
| 9/1 (二) | 🇦🇹 哈修塔特全日：天空步道 · 鹽礦 · 湖區遊船 |
| 9/2 (三) | 🇦🇹 聖沃夫岡 · 夏夫堡登山火車 (1,783m 俯瞰七湖) · 聖吉爾根 |
| 9/3 (四) | 🇦🇹 湖區慢行：Fuschlsee · Mondsee (Sound of Music 婚禮教堂) → 傍晚薩爾茨堡 |
| 9/4 (五) | 🇦🇹 薩爾茨堡全日：要塞 · 老城 · 米拉貝爾宮 · 修道院啤酒廠 |
| 9/5 (六) | 薩爾茨堡上午 → 🚗 SZG · ✈ LH1103 10:30→FRA · ✈ CX288 13:40→HKG |
| 9/7 (一) | ✈ CX288 法蘭克福→香港 07:20 抵達 |

## 航班

- 去程：AY100 HKG→HEL 20:55→05:35+1 (A350) + AY1011 HEL→TLL 07:00→07:40 (ATR 72)
- 中段：AY1475 HEL→VIE 16:55→18:20 (A320)
- 回程：LH1103 SZG→FRA 10:30→11:30 (Lufthansa) + CX288 FRA→HKG 13:40→07:20+1 (Cathay Pacific B777)

## 功能特性

- Leaflet.js 互動地圖，26 個編號標記點，三國分色顯示
- 飛行/渡輪路線連線 + 奧地利自駕路線標示
- 13 天詳細日程表，含具體航班號 (AY100, AY1011, AY1475, LH1103, CX288)
- 點擊行程卡片 → 地圖聚焦當天景點
- 點擊景點名稱 → 地圖平移 + 自動彈出資訊視窗
- 彈出視窗含景點圖片 + Wikipedia 詳細介紹連結
- 手機版：全螢幕分割式設計，地圖上半 + 底部可滑動面板

## 資訊來源

- Rick Steves Travel Forum
- lovetravellingblog.com
- theblogtrotter.com
- Wikivoyage / Wikipedia
- Finnair / Lufthansa / Cathay Pacific / Tallink Silja 官網 (航班資料)
