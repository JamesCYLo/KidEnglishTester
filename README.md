# 單字冒險島

適合 6～8 歲兒童的英文單字練習網站。Windows、iPad 和 iPhone 連到同一台 Windows 電腦時，會使用同一份孩子學習紀錄。

## Windows 啟動

1. 安裝 [Node.js 20 LTS](https://nodejs.org/)。
2. 在 `Z:\test` 開啟 PowerShell，執行 `npm install`。
3. 執行 `npm start`，本機開啟 `http://localhost:3000`。
4. 執行 `ipconfig` 找 Windows 的 IPv4 位址；iPad／iPhone 連相同 Wi-Fi 後開啟 `http://<IPv4位址>:3000`。
5. 若無法連線，在 Windows 防火牆新增 TCP 3000 的私人網路輸入規則。

首次進家長模式輸入至少 4 字元的密碼會完成設定。請勿直接將此網站暴露到網際網路。

## 備份

定期複製 `data/word-adventure.sqlite` 和 `uploads/`，即可保留所有學習紀錄與家長上傳圖片。
