# FFXIV Chocobo Racing Calculator

Final Fantasy XIV 仙人微彩計算器進階版 - 提供揭格建議、概率分析、風險評估的智能工具。

## 功能特色

- 🎯 **揭格建議** - 基於期望值計算最優揭格位置
- 📊 **概率分析** - 詳細的獲獎機率分析（大獎/高額/中等/其他）
- 📈 **線路分析** - 8 條線路的完整期望值和風險評估
- 🔄 **撤銷功能** - 支援 Ctrl+Z 快速撤銷
- 📱 **響應式設計** - 完美適配桌面和行動裝置

## 在線使用

[FFXIV Chocobo Racing Calculator](https://yourusername.github.io/ffxiv-chocobo-racing-calculator)

## 本地執行

1. 複製倉庫
```bash
git clone https://github.com/yourusername/ffxiv-chocobo-racing-calculator.git
cd ffxiv-chocobo-racing-calculator
```

2. 用瀏覽器開啟 `index.html`
   - 簡單方式：雙擊 `index.html`
   - 或使用本地伺服器（推薦）：
   ```bash
   # Python 3
   python -m http.server 8000
   # 訪問 http://localhost:8000
   ```

## 技術棧

- Vue.js 2.6
- 原生 HTML5 + CSS3
- 無後端依賴

## 獎勵表

| 總和 | MGP | 總和 | MGP |
|------|-----|------|-----|
| 6    | 10,000 | 15   | 180 |
| 7    | 36 | 16   | 72 |
| 8    | 720 | 17   | 180 |
| 9    | 360 | 18   | 119 |
| 10   | 80 | 19   | 36 |
| 11   | 252 | 20   | 306 |
| 12   | 108 | 21   | 1,080 |
| 13   | 72 | 22   | 144 |
| 14   | 54 | 23   | 1,800 |
| | | 24   | 3,600 |

## 使用說明

1. **輸入已知數字** - 最多輸入 4 個
2. **查看揭格建議** - 獲得期望值最高的位置
3. **分析所有線路** - 根據期望值、風險或大獎率排序
4. **做出選擇** - 選擇符合你風險偏好的線路

### 鍵盤快捷鍵
- **方向鍵** - 導航格子
- **Enter** - 前進到下一格
- **Ctrl+Z** - 撤銷最後操作
- **點擊已填格子** - 清除該數字

## 設定

編輯 `index.html` 中的 `data` 部分可自訂：
- `payouts` - 獎勵表
- `jackpotSums`, `highSums`, `mediumSums` - 獎勵分類

## 貢獻

歡迎提交 Issue 和 Pull Request！

## 授權

MIT License

## 免責聲明

本工具僅供參考，不保證百分百準確性。請自行驗證計算結果。
