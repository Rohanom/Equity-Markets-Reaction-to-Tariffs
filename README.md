# 📊Equity-Markets-Reaction-to-Tariffs

This project explores how **tariffs** impact company valuation using a simplified **Discounted Cash Flow (DCF)** framework. Through simulation and financial modeling, it demonstrates how a company’s **short-term valuation hit** due to tariff shocks can be **recovered — or even exceeded — through strategic reoptimization**.

> 🧠 *Key Idea*: Traders often price in policy shocks instantly. But companies adapt. Modeling this reoptimization unlocks actionable alpha.

---

## 🧮 Project Highlights

- ✅ **Baseline DCF Model**  
  A fictional business (lemonade stand) is valued using traditional DCF:
  - Revenue: $100/year
  - Cost: $60/year → Cash Flow = $40/year
  - Discount Rate: 10%
  - 10-year horizon + Terminal Value

- ⚠️ **Tariff Shock Simulation**  
  - Years 1–3: Cost rises to $75 → Cash Flow drops to $25
  - Years 4–10: Cost optimized to $58 → Cash Flow = $42
  - Recalculates DCF with new terminal value and compares to base case

- 📉 **Stock Price Repricing**  
  Simulates how stock price:
  - Drops instantly at policy shock
  - Gradually recovers through cost reoptimization
  - Ends up outperforming base case valuation

---

## 📊 Valuation Summary

| Scenario        | PV of Cash Flows | PV of Terminal Value | Total Equity Value |
|----------------|------------------|-----------------------|---------------------|
| **No Tariffs** | $245.78          | $154.22               | **$400.00**         |
| **With Tariffs** | $215.80        | $161.93               | **$377.72**         |

📉 Short-term drop, but improved long-run terminal value after adaptation.

---

## 📈 Stock Price Behavior

- 📍 **Day 20**: Shock from tariff imposition → stock drops
- 🛠️ **Post-Day 30**: Recovery begins as firm reoptimizes
- 🟢 **Outcome**: Price surpasses base case due to efficient adaptation

Visualized with simulated stock prices using `matplotlib` and `pandas`.

---

## 🔑 Key Takeaways

- Tariffs cause an immediate negative impact on cash flows and perceived value.
- Market participants often **overreact** to policy shocks.
- Well-managed firms **reoptimize operations** post-shock and recapture value.
- This **creates a value gap** that can be exploited quantitatively.
- Relevant in **policy-sensitive sectors** or **emerging markets**.

---

## 🧰 Tech Stack

- `Python`
- `NumPy`
- `Pandas`
- `Matplotlib`

---

## 🚀 Future Enhancements

- 📡 Incorporate real trade/tariff datasets from WTO/UNCTAD
- 🔄 Model tariff elasticity effects on revenue, not just costs
- 🧠 Extend to multi-firm, multi-sector simulations
- 🔍 Explore alpha capture via event-driven backtests

---

## 👤 Author

**Om Aditya**  
🎓 B.Tech @ IIT Jodhpur | Finance, Trading & ML Enthusiast  
🚀 Merging economics, quant finance, and machine learning for market insights  

- 🔗 [LinkedIn – omaditya8](https://www.linkedin.com/in/omaditya8)  
- 💻 [GitHub – Rohanom](https://github.com/Rohanom)

> “Policy creates constraints. Smart models create opportunity.”

---

Feel free to ⭐ this repo if you find it valuable!
