# 🎬 SMI / VTT → SRT 字幕轉換器

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/abc0922001/SMItoSRTSubtitleConverter?style=social)](https://github.com/abc0922001/SMItoSRTSubtitleConverter/stargazers)

免費、開源的線上字幕格式轉換工具。
支援 **SMI / SAMI / VTT → SRT**，可選擇使用 Google 翻譯將字幕轉為繁體中文。
所有處理皆在 **本地瀏覽器完成**，檔案不會上傳伺服器，隱私安全 🔒。

👉 專案連結：[SMItoSRTSubtitleConverter](https://github.com/abc0922001/SMItoSRTSubtitleConverter)

---

## ✨ 功能特色

* 📁 支援字幕格式：`.smi` / `.sami` / `.vtt`
* 🔄 一鍵轉換成標準 `.srt`
* 🌐 Google 翻譯整合（免費，無需 API Key）

  * 自動翻譯為繁體中文
  * ✅ 可選擇保留原文，產生雙語字幕
* 🖥️ 純前端運作，無伺服器依賴
* 🔒 100% 本地處理，隱私安全
* 📝 即時預覽與下載
* 🎨 現代化 UI 設計（拖放上傳、進度條、狀態提示）

---

## 🚀 使用方式

1. 下載或 Clone 本專案：

   ```bash
   git clone https://github.com/abc0922001/SMItoSRTSubtitleConverter.git
   cd SMItoSRTSubtitleConverter
   ```

2. 用瀏覽器直接開啟 `index.html`。

3. 上傳字幕檔：

   * 點擊或拖曳 `.smi / .sami / .vtt` 檔案到上傳區。
   * 工具會自動載入字幕資訊。

4. 選擇翻譯選項：

   * 不翻譯（僅格式轉換）
   * Google 翻譯 → 繁體中文（可選擇保留原文）

5. 點擊「開始轉換」➡ 預覽字幕 ➡ 下載 `.srt` 檔案。

---

## 📂 專案結構

```
SMItoSRTSubtitleConverter/
│── index.html       # 主程式（HTML / CSS / JS 全部在單檔內）
│── README.md        # 專案說明文件
│── LICENSE          # MIT 授權條款
```

---

## 🔧 技術細節

* **前端技術**：HTML + CSS + JavaScript
* **字幕解析**

  * `parseSMI()` → 解析 `.smi / .sami`
  * `parseVTT()` → 解析 `.vtt`
* **翻譯功能**

  * 使用 Google Translate Web API
  * 支援並行翻譯 + 自動重試
* **輸出**

  * `.srt` 格式，符合常見播放器標準
  * 可選擇輸出雙語字幕

---

## 📜 授權條款

本專案採用 **MIT License**，可自由使用、修改與散布。
詳見 [LICENSE](./LICENSE)。

---

## 🤝 貢獻方式

歡迎提出 Issue 或 Pull Request，一起改進功能與效能。
建議方向：

* ➕ 更多翻譯服務（如 DeepL、Azure Translate）
* ➕ 支援更多字幕格式（ASS/SSA）
* 📦 PWA / 桌面版（Electron）

---
