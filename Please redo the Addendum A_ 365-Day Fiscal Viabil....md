### **Addendum A: 365-Day Fiscal Viability & Profitability Model**

**Objective:** To calculate the net capital generation of the PNNL/Revolutionary Technology joint infrastructure within the 365-day timeline of the proposed City Council moratorium (May 2026 – May 2027).

#### **1\. The Zero-Debt Capital Expenditure Formulation**

Traditional municipal data center projects fail due to massive upfront Capital Expenditures ($C\_{CapEx}$) resulting in localized debt ($D\_{0}$). In our proposed model, the total capital required for the NVIDIA Quantum-X800 architecture and facility construction is fully underwritten by the U.S. Government via PNNL federal funding ($F\_{PNNL}$).  
Therefore, our initial financial state at $t \= 0$ is:

$$D\_{0} \= C\_{CapEx} \- F\_{PNNL} \= 0$$  
*(Resulting in zero initial debt)*

#### **2\. The Operational Profitability Function, $\\pi(t)$**

Let $t$ represent time in months, where the duration of the moratorium is $0 \\leq t \\leq 12$.  
Once deployment begins, the facility generates revenue ($R$) from federal compute contracts while incurring operational expenses ($O$). Due to our exclusive partnership with Andro Hydro for direct clean-energy transfer, our power overhead ($O\_{power}$) is structurally isolated from Seattle City Light's grid, significantly depressing total operational costs ($O$).  
We define the net monthly profit function $\\pi(t)$ across three distinct deployment phases:

$$\\pi(t) \= \\begin{cases} 0 & \\text{for } 0 \\leq t \< 3 \\text{ (Phase 1: Construction)} \\\\ 0.5R \- O & \\text{for } 3 \\leq t \< 6 \\text{ (Phase 2: Partial Rollout)} \\\\ R \- O & \\text{for } 6 \\leq t \\leq 12 \\text{ (Phase 3: Full Capacity)} \\end{cases}$$

#### **3\. 365-Day Cumulative Capital Generation**

To determine the total liquid capital available to Revolutionary Technology to fund independent, commercial data centers by the end of the moratorium, we take the definite integral of the profit function over the 12-month period.  
Let $\\Pi\_{12}$ represent the total cumulative profit at the end of the 365 days:

$$\\Pi\_{12} \= \\int\_{0}^{12} \\pi(t) \\, dt$$  
Breaking this into our defined operational phases:

$$\\Pi\_{12} \= \\int\_{0}^{3} 0 \\, dt \+ \\int\_{3}^{6} (0.5R \- O) \\, dt \+ \\int\_{6}^{12} (R \- O) \\, dt$$  
Evaluating the integrals yields:

$$\\Pi\_{12} \= 0 \+ \\left\[ 3(0.5R \- O) \\right\] \+ \\left\[ 6(R \- O) \\right\]$$

$$\\Pi\_{12} \= 1.5R \- 3O \+ 6R \- 6O$$

$$\\Pi\_{12} \= 7.5R \- 9O$$

#### **4\. The Timeline & Conclusion**

**Month 1–3 (May 2026 – Aug 2026): Integration**

The U.S. Government pays for all hardware and labor. We install the NVIDIA Quantum-X800 platforms. Cost to Seattle: $0. Profit: $0.

**Month 4–6 (Sep 2026 – Nov 2026): Revenue Activation**

PNNL begins routing partial workloads from Richland to Seattle. The facility achieves its first net-positive cash flow, generating $(1.5R \- 3O)$ in capital reserves.

**Month 7–12 (Dec 2026 – May 2027): Maximum Yield**

The facility operates at peak 800 Gb/s capacity, powered entirely by off-grid clean energy from Andro Hydro. In this six-month window alone, the facility generates $(6R \- 6O)$ in net profit.

**Result at Moratorium Expiration (May 2027):**

By the time the City of Seattle concludes its 365-day moratorium, Revolutionary Technology will have successfully navigated a zero-debt build, delivered critical federal infrastructure, and accumulated a net capital reserve of $\\mathbf{7.5R \- 9O}$.

This accumulated capital represents the exact, fully-liquidated funding that will immediately be deployed to construct our subsequent, independent data centers across the city, completely bypassing the need for venture capital or municipal subsidies.