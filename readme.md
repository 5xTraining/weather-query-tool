# Rust Weather CLI

這是一個使用 Rust 語言撰寫的工具，透過輸入的城市名稱，可查詢該城市的當前天氣。

## 功能

- 根據城市名稱取得其緯經度資訊（透過 Geocoding API）
- 根據緯經度資訊查詢該地點的當前天氣（透過 OpenWeatherMap API）

## 使用方法

在專案根目錄下新增一個 `.env` 檔案，並確保已經設置了必要的環境變數，檔案名稱可參考 `.env.example`。

然後執行程式：

```bash
cargo run -- --city 城市名稱
```
