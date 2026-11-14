---
---

## About

I am a machine learning researcher and engineer working on climate, health, and society. I did my MS in Computer Science at UC San Diego and I am currently based in India.

Right now I am working on extreme weather prediction, with a focus on tropical cyclones and early warning. Before this, I built LLM systems for healthcare at Oracle, did research in the [Ideker Lab](https://idekerlab.org/){:target="_blank" rel="noopener"} at UC San Diego, and worked on machine learning for cybersecurity at TCS Research in Pune. I also have a background in clinical NLP and AI fairness.

I like finding out whether an idea actually works, then building it into something people use, picking up whatever new method, tool, or field the problem needs along the way.

I am currently applying to PhD programs, and I am always happy to talk about research collaborations.


## Selected work

{% include selected-work.html %}

[More on the Research page →](/research/){:.all-pubs}

{% comment %} WiML 2026 poster: hidden from Selected work (non-archival, not presenting); still in the timeline. Kept here to turn into a blog post.
### Which Information Matters for Rapid Intensification of Tropical Cyclones? A Global-Basin Feature Ablation Study

*Sukhada Ghewari and Shardul Deshpande*

**WiML Workshop poster, NeurIPS 2026**

Rapid intensification, a jump of 30+ knots in peak winds within 24 hours, is one of the hardest problems in cyclone forecasting and leaves coastal communities little time to prepare. Using 80,000+ observations from 4,000+ storms worldwide (IBTrACS and ERA5, 1980–2025), I tested which information actually drives prediction, using 5-fold cross-validated feature ablations on the training years.

ERA5 environmental predictors add the most: removing them causes the largest drop in AUPRC of any feature group. On storms from 2016–2025, held out from all training and model selection, the final XGBoost model reaches 0.42 AUPRC (about 4× the no-skill baseline) and 0.86 ROC-AUC, and catches about three quarters of rapid-intensification events at a recall-focused threshold.

<!-- [Poster](https://){:target="_blank" rel="noopener"} and [Code](https://github.com/sukhadaghewari/...){:target="_blank" rel="noopener"} -->

{% endcomment %}

{% comment %} Hidden for now. Delete this line and the matching one at the end of the section to show it again.
### [Poster title]

**WiML poster, NeurIPS 2026**

[One line on the question and what you found.]

[Poster](https://)

### Predicting rapid intensification of tropical cyclones

**In progress**

Machine learning for early warning of cyclones that strengthen suddenly, one of the hardest forecasting problems for India's coasts.

[Code](https://)
{% endcomment %}

## News

{% include news.html latest=5 %}
