# Mathematical Specification: System Dynamics and Circuit Logic

## 1. The Energy Constant: Why "2.0 Million"?
The simulator uses a base unit of **200 (2.0 Million JPY)** for monthly household expenditure. This is not a "wallet" figure; it is a **System Maintenance Load**.

### 1.1 Total System Energy ($E_{total}$)
To calculate the energy required to sustain one unit (household) of the system, we aggregate the total flow of public funds, including the National Budget (General + Special Accounts) and Local Government Budgets.

$$E_{total} \approx 1,200 \text{ Trillion JPY / year}$$

### 1.2 Normalization by Household Units ($N_h$)
Total energy is divided by the number of grounding points (households) to find the "Base Load" required to keep the physical infrastructure (roads, grids, debt interest) functional for one person/family.

$$L_{base} = \frac{E_{total}}{12 \text{ months} \times 50,000,000 \text{ households}} = \mathbf{2,000,000 \text{ JPY / month}}$$

**The Logic:** If a household only feels a benefit of 200,000 JPY but the system burns 2,000,000 JPY to deliver it, the **System Efficiency is 10%**. The remaining 90% is lost to structural friction (overhead, middle-men, and debt servicing).

---

## 2. Fiscal and Debt Logic

### 2.1 Total Expenditure ($Out_{total}$)
The cost of running the state increases linearly with the interest rate due to debt servicing.

$$Out_{total} = B_{out} + (r_{jp} \times 15)$$
*   $B_{out}$: Base policy expenditure (Starts at 200).
*   $r_{jp}$: Central Bank Interest Rate.
*   $15$: The **Debt Sensitivity Coefficient**. (High rates = higher burning of public energy).

### 2.2 Total Income ($Inc_{total}$)
$$Inc_{total} = B_{inc} + \text{Retention Penalty}$$
*   $B_{inc}$: Tax revenue (Starts at 150).
*   If corporate retention is high, a minor "stagnation tax" is added, but it does not offset the loss in circulation.

---

## 3. Market vs. Real Life (Signals vs. Ground)

The simulator separates indicators into **Blue (Signals/Expectations)** and **Orange (Physical Work/Survival)**.

### 3.1 Market Signal: Stock Price ($S$)
Stock prices are boosted by liquidity and global interest rates but reduced by structural distortion.

$$S = \frac{100 - (10 \cdot r_{jp}) + (4 \cdot r_{usa}) + (0.5 \cdot G) + \text{Policy Bonuses}}{D}$$
*   $r_{usa}$: US Federal Interest Rate.
*   $G$: Corporate Greed/Retention level.
*   $D$: **Structural Distortion Index**. (Friction caused by inefficient public spending).

### 3.2 Physical Reality: Inflation ($In$)
Inflation is primarily driven by the "Currency Gap" between domestic and foreign rates.

$$In = (100 + (Gap_{rate} \times 15) - (r_{jp} \times 8) + P_{push}) \times P_{shield}$$
*   $Gap_{rate} = r_{usa} - r_{jp}$.
*   $P_{push}$: Cost-push inflation from specific policies.
*   $P_{shield}$: Efficiency shield from infrastructure investment.

---

## 4. Grounding: Net Disposable Income ($Y_{net}$)

This is the most critical metric. It represents the "Earth" of the circuit. If $Y_{net}$ falls below zero, the system suffers a **Total Breakdown**.

### 4.1 The Income Bonus ($Y_{bonus}$)
The energy released by the government (Deficit) or distributed by corporations.
$$Y_{bonus} = (Out_{total} - Inc_{total}) \times 0.7 + (100 - G) \times 0.4$$

### 4.2 The Net Income Equation
The final survival metric for the grounding point (household).

$$Y_{net} = 100 + Y_{bonus} - \Delta In \cdot 1.8 - \Delta M \cdot 1.0 + (r_{jp} \times 2)$$
*   $\Delta In$: Impact of Inflation (weighted at 1.8x).
*   $\Delta M$: Impact of Mortgage/Debt interest (weighted at 1.0x).
*   $r_{jp} \times 2$: Minor benefit from savings interest.

---

## 5. System Constants and Friction Coefficients

| Variable | Engineering Meaning | Simulator Impact |
| :--- | :--- | :--- |
| **Friction (D)** | Efficiency of energy transfer. | High distortion divides the stock value. |
| **Leakage ($\lambda$)** | Rate at which capital exits the local loop. | Expressed via the gap between $Out_{total}$ and $Y_{net}$. |
| **Joule Heat** | Wealth turning into speculation/volatility. | Occurs when interest rates are too low for the "Expected" flow. |
| **Grounding** | Direct benefit to the household. | The only way to prevent a negative $Y_{net}$. |

## Summary of the "Deadlock"
The simulation demonstrates that $r_{jp}$ (Interest Rate) acts as a **Dual-Edged Resistor**:
1.  **Lowering $r_{jp}$** reduces mortgage pain but increases Inflation Heat (via weak Yen).
2.  **Raising $r_{jp}$** cools Inflation but exponentially increases Mortgage Load and Government Debt Burning.

**The Debugging Goal:** Finding the balance where $Y_{net} > 0$ while minimizing the "Energy Waste" (System Load vs. Ground Benefit).
