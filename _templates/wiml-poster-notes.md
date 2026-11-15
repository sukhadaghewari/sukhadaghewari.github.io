<!--
  Notes for the WiML 2026 poster, saved from the old home page so they can
  become a blog post later. Nothing in _templates is published.
-->

### Which Information Matters for Rapid Intensification of Tropical Cyclones? A Global-Basin Feature Ablation Study

*Sukhada Ghewari and Shardul Deshpande*

**WiML Workshop poster, NeurIPS 2026**

Rapid intensification, a jump of 30+ knots in peak winds within 24 hours, is one of the hardest problems in cyclone forecasting and leaves coastal communities little time to prepare. Using 80,000+ observations from 4,000+ storms worldwide (IBTrACS and ERA5, 1980–2025), I tested which information actually drives prediction, using 5-fold cross-validated feature ablations on the training years.

ERA5 environmental predictors add the most: removing them causes the largest drop in AUPRC of any feature group. On storms from 2016–2025, held out from all training and model selection, the final XGBoost model reaches 0.42 AUPRC (about 4× the no-skill baseline) and 0.86 ROC-AUC, and catches about three quarters of rapid-intensification events at a recall-focused threshold.

<!-- [Poster](https://){:target="_blank" rel="noopener"} and [Code](https://github.com/sukhadaghewari/...){:target="_blank" rel="noopener"} -->
