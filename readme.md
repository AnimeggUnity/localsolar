# ☀️ 太陽能系統理論潛力月度計算器（Local Solar Potential Calculator）

[👉 點我立即試用 Demo](http://580.blias.com/solar/solar.html)

---

這是一個簡單的網頁工具，可以幫你用地圖點地點、選月份，估算那個地點在理想晴天下的**太陽能發電潛力**。

你可以：

- 點選地圖或選擇縣市快速定位
- 輸入面板瓦數、數量、傾角與方位角
- 自訂估計損耗（陰影、老化、線損等）
- 計算該月的理論最大發電量
- 查詢歷史實際日照資料（來自 Open-Meteo）
- 顯示每日發電估算與日照表格
- 顯示該月最佳理論角度、全年建議角度
- 自動儲存上次的設定

無需後端，所有運算都在前端完成，支援桌機與手機瀏覽器。

---

## 🌍 Local Solar Monthly Potential Estimator

[👉 Try Live Demo Here](http://580.blias.com/solar/solar.html)

A lightweight web-based tool that lets you:

- Click on a map or select a location (Taiwan's cities)
- Enter your solar panel setup (watts, tilt, azimuth, losses)
- Estimate **theoretical maximum energy production** for a given month
- Fetch **actual daily sun hours** from historical Open-Meteo data
- View suggested **optimal tilt & azimuth** (monthly and yearly)
- Save your last setup locally (via localStorage)

All calculations are done **entirely in-browser** — no backend required.

---

## 🛠 技術技術 / Tech Stack

- HTML + CSS + JavaScript (Vanilla)
- Leaflet.js 地圖功能
- Open-Meteo API（歷史日照資料）
- 完全前端運算，無伺服器依賴

---

## 🚀 開始使用 / How to Use

1. 打開 [`solar.html`](solar.html) 或點擊上方的 Demo 網址。
2. 選擇縣市或在地圖上點選位置。
3. 輸入你的系統資訊與損耗參數。
4. 一鍵計算理論太陽能發電潛力。

---

## 📌 注意事項 / Notes

- 理論發電量假設理想晴天（1000W/m² 垂直輻射）
- 結果僅供參考，實際發電會因天氣與環境條件而有所不同
- 請確保經緯度格式正確（例如：`23.588093, 120.630267`）

