**ABSTRACT**
Financial markets are inherently unstable, characterised by structural breaks, regime shifts, volatility
clustering, and persistently low signal-to-noise ratios. These conditions challenge the reliability and
generalisability of modern machine-learning (ML) models, which are often developed under
assumptions of stationarity that rarely hold in practise. This multi-vocal literature review synthesises
perspectives across academic research, practitioner reports, and regulatory guidance to evaluate how
ML models behave under distribution shift and what constitutes robustness in machine learning
models applied to financial forecasting. Academic studies highlight the theoretical fragility of
complex models – driven by overfitting, high variance, and instability under drift – while practitioner
literature (e.g., AQR, Robeco, CFA Institute) emphasises real-world model decay, operational risk,
and the failure of ML systems in live environments. Regulatory frameworks, particularly the
Federals Reserve’s Model Risk Management (SR 11-7), further underscore robustness, validation,
interpretability, and uncertainty management as essential for safe deployment. Drawing together
theoretical foundations from statistical learning theory, concept-drift research, causal robustness,
and model-risk governance, this review consolidates evidence on how ML models respond to
simulated drift, covariate perturbations, regime changes, and volatility shocks. Across sources, a
recurring theme emerges; accuracy in stable training environments provides limited insight into real-
world performance. Instead, robustness – captured through stability, generalisation under
uncertainty, interpretability, and resilience to drift – is the defining criterion for trustworthy financial
ML. This review proposes an integrated framework for evaluating robustness in financial time-series
forecasting that reflects the insights of diverse lenses and contexts. The findings offer a unified
foundation for future empirical work and inform practitioners and researchers seeking to design ML
models capable of withstanding the dynamic, adversarial, and non-stationary nature of financial
markets.

**Keywords Machine Learning** ･ Robustness ･ Regime Switching ･ Distribution Shift ･ Interpretability and
Explainability ･ Generalization Under Uncertainty ･ Governance ･ Economic Viability
