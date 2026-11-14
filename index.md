---
---

## About

I am an AI/ML engineer and applied researcher working on machine learning for climate, health, and society. I did my MS in Computer Science at UC San Diego and I am currently based in India.

Right now I am working on extreme weather prediction, with a focus on tropical cyclones and early warning. Before this, I built LLM systems for healthcare at Oracle, and worked on machine learning for cybersecurity at TCS Research. I also have a background in clinical NLP and AI fairness.

I like finding out whether an idea actually works, then building it into something people use, picking up whatever new method, tool, or field the problem needs along the way.


## Selected work

### Can Multimodal LLMs Predict Rapid Intensification? A Leakage-Controlled Zero-Shot Benchmark for Tropical Cyclones

*Sukhada Ghewari · Harshal Tupsamudre*

**WACV 2027 · GeoCV Workshop paper**

Can general-purpose multimodal LLMs predict rapid intensification with no task-specific training, and does satellite imagery help? A zero-shot benchmark of six commercial LLMs on 2,485 six-hourly forecast cases from 140 storms (2016–2025), combining IBTrACS best tracks, ERA5 predictors and GridSat-B1 infrared imagery. Storm names, dates and locations are removed so models can't recognise the storm and recall what happened.

All six models reach 0.22–0.34 PR-AUC, two to three times chance, with Claude Sonnet 5.5 best at 0.344. Adding satellite images brings no clear gain, and an XGBoost model trained on 1980–2015 storms still beats every LLM (0.439 PR-AUC) using only 16 tabular features.

<!-- [Paper](https://){:target="_blank" rel="noopener"} · [Code](https://github.com/sukhadaghewari/...){:target="_blank" rel="noopener"} -->

### Tropical Cyclone Rapid Intensification (RI) Prediction using Machine Learning

*Sukhada Ghewari · Adway Mitra*

**NeurIPS 2026 · Tackling Climate Change with Machine Learning (TCCML) Workshop tutorial**

A hands-on notebook that frames rapid intensification as a rare-event classification problem. It builds interpretable features from best-track records, GridSat satellite cloud-cover data and atmospheric and oceanic reanalysis, then trains and evaluates a model with metrics suited to imbalanced, safety-critical forecasting, including probability calibration and distribution shift. It also shows how ML-based RI prediction could give forecasters more lead time to prepare for sudden storm strengthening and issue timely warnings.

<!-- [Notebook](https://){:target="_blank" rel="noopener"} · [Code](https://github.com/sukhadaghewari/...){:target="_blank" rel="noopener"} -->

{% comment %} WiML 2026 poster: hidden from Selected work (non-archival, not presenting); still in the timeline. Kept here to turn into a blog post.
### Which Information Matters for Rapid Intensification of Tropical Cyclones? A Global-Basin Feature Ablation Study

*Sukhada Ghewari · Shardul Deshpande*

**NeurIPS 2026 · WiML Workshop poster**

Rapid intensification, a jump of 30+ knots in peak winds within 24 hours, is one of the hardest problems in cyclone forecasting and leaves coastal communities little time to prepare. Using 80,000+ observations from 4,000+ storms worldwide (IBTrACS and ERA5, 1980–2025), I tested which information actually drives prediction, using 5-fold cross-validated feature ablations on the training years.

ERA5 environmental predictors add the most: removing them causes the largest drop in AUPRC of any feature group. On storms from 2016–2025, held out from all training and model selection, the final XGBoost model reaches 0.42 AUPRC (about 4× the no-skill baseline) and 0.86 ROC-AUC, and catches about three quarters of rapid-intensification events at a recall-focused threshold.

<!-- [Poster](https://){:target="_blank" rel="noopener"} · [Code](https://github.com/sukhadaghewari/...){:target="_blank" rel="noopener"} -->

{% endcomment %}

{% comment %} Hidden for now. Delete this line and the matching one at the end of the section to show it again.
### [Poster title]

**NeurIPS 2026 · WiML poster**

[One line on the question and what you found.]

[Poster](https://)

### Predicting rapid intensification of tropical cyclones

**In progress**

Machine learning for early warning of cyclones that strengthen suddenly, one of the hardest forecasting problems for India's coasts.

[Code](https://)
{% endcomment %}

## News

{% include news.html latest=5 %}
