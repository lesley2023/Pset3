# Problem Set 3: Lecture Guide

Based on [Problem Set 3](<Problem Set 3.pdf>) and the slides in `Lecture Notes/Andrei Version`.

**Overview:** Question 1 mainly tests Module 3; Question 2 tests Module 4; Questions 3–4 test Module 5. Modules 1–2 provide supporting material on asset-pricing puzzles and estimation.

**Numbering:** “Slide” refers to the printed label (for example, 1.6). “PDF page” counts from the title page as page 1. A printed slide label may repeat across several PDF pages. The references below are a topic mapping; some questions extend the arguments presented in the slides.

## Question 1: Module 3 — The CAPM & Factor Models

[Module 3 PDF](<../Lecture Notes/Andrei Version/BUSFIN 8200 - Module 3 (print version).pdf>)

| Part | Corresponding slides / PDF pages | What it tests |
|---|---|---|
| **1a** | **1.6** (p. 11), **1.9** (p. 16). Optional direct derivation: appendix p. 84. | Mean-variance portfolio optimization with a risky baseline asset; simplification when the baseline is risk-free. |
| **1b** | **2.2–2.5** (pp. 24–27), especially **2.4** (p. 26). | Turning individual optimal portfolio choice into the CAPM through representative-investor market clearing; covariance and beta representations. |
| **1c** | **1.4** (p. 8), plus **1.9** (p. 16). | Maximum-Sharpe-ratio weights and normalization; relating the tangency portfolio to mean-variance risk aversion. |
| **1d** | **1.4** (p. 8) and especially **3.2**, “Motivation: The Maximum Sharpe Ratio Portfolio” (p. 45). | Combining the market with orthogonal alpha strategies; the GRS Sharpe-ratio improvement result; using the maximum-Sharpe portfolio to motivate a multifactor SDF. The question extends the slide’s argument into an explicit derivation. |
| **1e(i)** | **4.6**, “PCA for Unconditional Latent Factor Model” (pp. 70–73; start with p. 70). | Extracting latent factors from return covariance and normalizing factor volatility. |
| **1e(ii)–(iii)** and discussion | **3.3**, “The Fama & French 3-Factor Model” (pp. 46–47); **4.6** (pp. 70–73); **3.12**, “Limitations of Reduced Form Factor Models” (p. 59). | Comparing market-only versus FF3 explanations of the PCs; distinguishing statistical comovement from an economic explanation of risk premia. See Module 2 below for Newey–West inference. |

## Question 2: Module 4 — The Intertemporal CAPM

[Module 4 PDF](<../Lecture Notes/Andrei Version/BUSFIN 8200 - Module 4 (print version).pdf>)

| Part | Corresponding slides / PDF pages | What it tests |
|---|---|---|
| **2a** | **1.5–1.6** (pp. 11–12). **Essential derivations:** appendix p. **52**, “The cwₜ Solution (ψ = 1),” and pp. **54–55**, “The Intertemporal Portfolio Allocation SDF (ψ = 1).” | Epstein–Zin consumption and portfolio first-order conditions; constant consumption-to-wealth ratio when ψ = 1; log SDF and lognormal covariance pricing. |
| **2b** | **1.2–1.3** (pp. 6–7), **1.6–1.8** (pp. 12–15). | Portfolio log-return approximation; separating myopic demand from intertemporal hedging demand; interpreting the hedge when γ > 1. |
| **2c** | **2.3**, “The ICAPM Derivation” (p. 29), compared with **1.6** (p. 12). | Why an individual investor’s optimality condition becomes an equilibrium asset-pricing restriction only after identifying their portfolio with aggregate market wealth. |
| **2d** | **1.8** (pp. 14–15), **2.6**, “The ICAPM (using News)” (p. 36). **Derivation:** appendix pp. **58–59**, “The Recursive Equation for vwₜ.” | Solving the value-to-wealth recursion forward; expected-return news and variance news as changes in investment opportunities. |
| **2e** | **2.8** (pp. 41–42) and especially **2.10**, “An Intertemporal Risk Factor Model” (pp. 45–50). Also Module 2 below. | Implementing the ICAPM with tradable market, reinvestment, and volatility factors; interpreting SDF coefficient signs through γ; estimating the linear SDF by GMM. |

## Question 3: Module 5 — The Consumption CAPM

[Module 5 PDF](<../Lecture Notes/Andrei Version/BUSFIN 8200 - Module 5 (print version).pdf>)

| Part | Corresponding slides / PDF pages | What it tests |
|---|---|---|
| **3a** | **1.2–1.4** (pp. 6–9). **Derivation:** appendix p. **88**, “The Consumption CAPM (CCAPM).” | Consumption-based SDF under power utility; representative-investor and endowment-economy assumptions that turn individual Euler equations into the CCAPM. |
| **3b** | **1.5–1.8** (pp. 10–13). | Risk-free-rate decomposition; consumption covariance pricing; equity premium and equity volatility puzzles. Module 1 supplies the original excess-volatility background. |
| **3c** | **3.4–3.6** (pp. 55–57). Optional derivations: appendix pp. **98–100**. | How rare disasters lower the risk-free rate and raise the equity premium relative to the canonical CCAPM. |
| **3d** | **2.2–2.3** (pp. 26–27), **2.6–2.7** (pp. 32–33). **Derivations:** appendix p. **89** and pp. **91–95**, especially p. **93** for the Δc and vc SDF. | Epstein–Zin preferences; separating risk aversion from IES; long-run consumption and volatility news as additional priced risks. |
| **3e** | **4.2–4.6** (pp. 67–73), especially **4.5–4.6** (pp. 71–73). **Derivation:** appendix p. **101**. | External habit, surplus consumption, and time-varying effective risk aversion; why the equity premium becomes more volatile. |

## Question 4: Module 5 — Numerical Implementation of Campbell–Cochrane

Use the same Module 5 PDF linked above.

| Part | Corresponding slides / PDF pages | What it tests |
|---|---|---|
| **4a** | **4.4–4.7** (pp. 70–74), especially **4.7**, “The Model Numerical Solution: Function Iteration” (p. **74**). | Solving the price-dividend functional equation using a state grid, numerical integration, interpolation, and iteration. |
| **4b** | **4.5** (pp. 71–72), **4.6** (p. 73), and **4.8** (pp. 75–83) for comparison figures. | Recovering expected equity returns from the solved price-dividend function and comparing them with the risk-free rate across surplus-consumption states. |
| **4c** | **4.4–4.7** (pp. 70–74), with calibration and simulation results in **4.8** (pp. 75–83). | Simulating consumption, dividends, and the habit state; constructing returns and evaluating annual equity-premium moments. |

## Supporting References: Modules 1–2

### Module 2: Estimation for Questions 1e and 2e

[Module 2 PDF](<../Lecture Notes/Andrei Version/BUSFIN 8200 - Module 2 (print version).pdf>)

- **Slide 2.4 (p. 22):** HAC / Newey–West covariance estimation.
- **Slide 2.7 (p. 25):** OLS-as-GMM connection, useful for regression inference in 1e.
- **Slides 3.5–3.6 (pp. 38–39):** Linear-SDF GMM estimator and its just-identified simplification; especially relevant for 2e.

### Module 1: Excess Volatility for Questions 3b and 3e

[Module 1 PDF](<../Lecture Notes/Andrei Version/BUSFIN 8200 - Module 1 (print version).pdf>)

- **Slide 1.4 (pp. 10–11):** The Excess Volatility Puzzle and its implication that expected returns vary over time.

## Study Priority

The **appendices are particularly useful for 2a, 2d, 3a, 3d, and 3e**: the main slides state many results, while those appendix pages provide the derivations the problem set asks you to reproduce.
