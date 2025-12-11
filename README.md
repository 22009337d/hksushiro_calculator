# 🍣 香港壽司郎計數機 (Sushiro Bill Counter)

邊食野邊計數，即時知道你食左幾錢! Track your Sushiro bill in real-time with our mobile-friendly counter app.

## 📱 Features

- ✅ **實時計數** - 紅碟($12) / 銀碟($17) / 金碟($22) / 黑碟($27)
- ✅ **40+ 特別料理** - 料理、甜品、飲品、酒類全部搞掂
- ✅ **自動計算** - 包括 10% 服務費
- ✅ **響應式設計** - iOS / Android / Desktop 完美適配
- ✅ **PWA 支持** - 可安裝至主屏幕，無需 App Store
- ✅ **離線可用** - 保存計數數據

## 🚀 快速開始

### 網頁版本（即刻用）
在任何瀏覽器打開：
```
https://yourusername.github.io/hksushiro-calculator/
```

### 手機版本（安裝為 App）

**iOS（Safari）:**
1. 開啟呢個網址
2. 按下方「分享」按鈕
3. 選「加入主屏幕」

**Android（Chrome）:**
1. 開啟呢個網址
2. 按右上角「⋮」(三點)
3. 選「安裝應用程式」或「Install app」

## 🎯 使用方式

1. **選擇碟子顏色** - 按 +/- 按鈕計數
2. **添加特別料理** - 點擊「特別菜單」查看 40+ 菜式
3. **輸入其他金額** - 自動計算額外項目
4. **查看總額** - 底部顯示加服務費後的金額
5. **重置** - 按「全部重置」開始新一餐

## 📊 技術細節

- **前端框架** - Vanilla HTML5 / CSS3 / JavaScript（無依賴）
- **存儲** - LocalStorage（計數數據本地保存）
- **PWA** - Service Worker 支持離線使用
- **設計** - 移動優先、深色模式支持、Safe Area 適配

## 🔧 開發者資訊

### 本地運行
```bash
# 克隆 repo
git clone https://github.com/yourusername/hksushiro-calculator.git
cd hksushiro-calculator

# 用任何 static server 運行
python -m http.server 8000
# 或用 Live Server

# 打開瀏覽器
# http://localhost:8000
```

### 檔案結構
```
├── index.html          # 主應用（包含所有 CSS + JS）
├── manifest.json       # PWA 配置
└── README.md          # 此文件
```

### 技術堆疊
| 功能 | 技術 |
|------|------|
| UI Framework | HTML5 + CSS3 Variables |
| Interactivity | Vanilla JavaScript (ES6+) |
| State Management | JavaScript Objects + DOM |
| Styling | Mobile-first Responsive CSS |
| PWA | Web App Manifest + Service Worker Ready |
| Icons | Emoji + SVG |

## 📈 未來計劃

- [ ] 廣告集成（Google AdMob）
- [ ] Affiliate 推薦鏈接（Klook, Deliveroo）
- [ ] 多語言支持（英文、日文）
- [ ] 用戶數據統計
- [ ] iOS / Android 原生應用（Capacitor）

## 🎓 在你的 CV 上這樣寫

**Frontend Developer / Mobile Engineer:**
```
Sushiro Bill Counter (Personal Project)
- Built a responsive PWA using vanilla HTML5/CSS3/JavaScript, 
  handling real-time calculations with 40+ menu items and 10% service charge
- Implemented as single-page app with localStorage persistence 
  and mobile-first design (iOS safe areas, notch support)
- Deployable as standalone web app (iOS/Android) via PWA manifest
- Future: iOS app via Capacitor, AdMob monetization
```

## 💰 Monetization Strategy

目前 100% 免費。未來計劃：

1. **AdMob Banner 廣告** - 底部廣告位置
2. **Affiliate Links** - Klook、Deliveroo 推介
3. **Premium 版本** - 無廣告 + 雲端同步（可選）

**收入預測：**
- 每日 100 個活躍用戶 + Banner 廣告 → 年收約 HK$800+（可覆蓋 Developer 年費）

## 📝 License

MIT License - 自由使用、修改、商用

## 🙏 致謝

感謝壽司郎提供靈感！🍣

---

**想幫手改進？** 歡迎 Fork 或提交 Pull Request!

**有問題？** 開啟 Issue 或聯絡我。

**想轉為 iOS App？** 見 Capacitor 分支 (coming soon)
