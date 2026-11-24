音日 v1.0
將資料夾內所有檔案部署至同一 HTTPS 靜態網站（例如 GitHub Pages）。iPhone 使用 Safari 開啟網站，分享 → 加入主畫面，再從主畫面開啟、匯入音樂。首次須連網完成快取。Mac 可在資料夾內執行 python3 -m http.server 8000，並開啟 http://localhost:8000 測試。iPhone 透過區域網路 HTTP 不保證支援 Service Worker，正式使用請採 HTTPS。音樂保存在各裝置各自的 IndexedDB，並不會跨裝置同步。請保留原檔。iOS 鎖定螢幕後自動接續播放與睡眠定時仍受系統限制。此版本尚未在實體 iPhone 測試。
