# ☀️ 太陽能系統理論潛力月度計算器（Local Solar Potential Calculator）

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

## 🚀 開始使用 / Try it Out

直接打開 `solar.html` 就能使用！  
Open `solar.html` in your browser — no setup needed.

---

## 📌 注意 / Notes

- 理論發電量假設理想晴天（1000W/m² 垂直輻射）
- 結果僅供參考，實際發電會因天氣與環境而不同
- 若出現錯誤提示，請檢查經緯度格式是否正確

---

## 📄 License

MIT License.
