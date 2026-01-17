# BMNR Power Law Pine Script 📈


## 📖 Introduction / 简介
Adaptive Power Law Channels is a ~~professional-grade~~ TradingView indicator designed for crypto assets (optimized for ETH). Unlike traditional static power law models, this version introduces ATR Dynamic Volatility Correction, ~~effectively~~ filtering out "fake breakouts" during high volatility.

BMNR 自适应幂律通道 是一款专为加密资产（针对 ETH 优化）设计的 ~~专业级~~ TradingView 指标。不同于传统的静态幂律模型，引入了 ATR 动态波动率修正**，能~~有效~~过滤剧烈波动带来的“假突破”信号。

---

## ✨ Key Features / 核心功能

* **Adaptive Power Law Model: Multi-level trajectory calculation based on specific Scale (A) and Exponent (B) parameters.
* 自适应幂律模型**：基于特定系数与指数的多级轨道计算。


* **ATR Volatility Elasticity: Uses Average True Range (ATR) to dynamically expand or contract the bands, preventing premature entry during market flush-outs.
* ATR 波动率弹性**：利用平均真实波幅动态调整轨道宽度，防止在极端洗盘行情中过早入场。


* **Real-time Dashboard: A clean UI panel in the top-right corner showing current premium/discount and deviation levels.
* 实时数据看板**：右上角 UI 面板实时显示价格偏离度、溢价率及当前轨道状态。


* **Signal Filters: Visual buy/sell labels with background highlighting for extreme valuation zones.
* 信号过滤**：自动标注抄底（BUY）与逃顶（SELL）信号，并辅以背景高亮提示。



---

## 🛠 Parameters / 参数设置

| Parameter (参数) | Description (说明) |
| --- | --- |
| `Power Law (A/B)` | Core model constants for Top, Mid, and Bottom bands. |
| `ATR Multiplier` | Controls how much volatility affects the band width. |
| `Time Filter` | Restricts signal plotting to a specific historical range. |

---

## 🚀 How to Use / 如何使用

1. Copy the code from `BMNR_Adv_Signal.pine`.
2. Open **TradingView -> Pine Editor.
3. Paste the code and click Add to Chart.
4. *(Optional)* Customize the Scale/Exponent parameters in the settings to fit other assets

1. 复制本仓库中的 BMNR_Adv_Signal.pine 代码。
2. 打开 TradingView -> Pine Editor**。
3. 粘贴代码并点击 **Add to Chart**。
4. *(可选)* 在设置中微调 A/B 系数以适配 ETH 其他交易对。

---

## ⚠️ Disclaimer / 免责声明

Financial trading involves significant risk. This script is for educational and research purposes only. **Remember: Indicators are tools, not crystal balls.

投资有风险，入市需谨慎。本脚本仅供研究与教学使用。**请记住：指标只是工具，不是预测未来的水晶球。**

---

### 🤝 Contributing

If you have better parameters for other crypto assets, feel free to open a Pull Request!

如果你有针对其他币种更好的模型参数，欢迎提交 **PR**！
