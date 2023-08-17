---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2013, 2011, 2010, 2009, 2008]
nav: true
weight: 2
---

[[Google scholar](https://scholar.google.com/citations?user=BUFSF_8AAAAJ&hl=en)] | [[ResearchGate](https://www.researchgate.net/profile/Zhou-Huang-3)] | [[View by topic](https://pku-geocomp.com/research/)]

#### **Published Papers**

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f hz_refs -q @*[year={{y}}]* %}
{% endfor %}

</div>

<br>

#### **Articles submitted and in review**
1. Bao, Y.; <u><b>Huang, Z.</b></u>*; Mao R.; Liu G.; Wang H.; Yin G. High-resolution mapping of material stocks in the built environment across 50 Chinese cities. Resources, Conservation & Recycling, 2023, with major revision.

2. Qi, H.; <u><b>Huang, Z.</b></u>*; Chen, Y.; Zhang, Y.; Gao, Y. A heterogeneous streaming processing framework for online map matching based on Spark and GPU computing. International Journal of Geographical Information Science, 2023, resubmitted.

3. Jiang, Y.; <u><b>Huang, Z.</b></u>*; Li, L.; Dong Q. Local-global dual attention network (LGANet) for population estimation using remote sensing imagery. Resources, Environment and Sustainability, 2023, with major revision.

4. iang, Y.; <u><b>Huang, Z.</b></u>*; Zhou, X.; Chen X. Evaluating the impact of urban morphology on urban vitality: an exploratory study using big geo-data. International Journal of Digital Earth, 2023, under review.

5. Du, H.; <u><b>Huang, Z.</b></u>*; Zhang Y.; Zhang Y. An optimized edge-focused Siamese network for monitoring new illegal buildings using satellite images. IEEE Transactions on Geoscience and Remote Sensing, 2023, with resubmission.

6. Zheng, J.; <u><b>Huang, Z.</b></u>*; Zhou X.; Cao X.; Wang H. Spatiotemporal analysis of CO2 emissions and emission reduction potential of Beijing buses using smart card data. Sustainable Cities and Society, 2023, under review.

7. Fu, C.; <u><b>Huang, Z.</b></u>*; Scheuer, B.; Lin, J.; Zhang, Y. Integration of dockless bike-sharing and metro: Prediction and explanation at origin-destination level. Sustainable Cities and Society, 2023, under review.

8. Wang, Z.; Ruan, S.; Zhou, H.; Zhang, S.; Wang, Y.; Liu, Y.; <u><b>Huang, Z.</b></u>*. TSP: A lightweight mlp for efficient multivariate time series forecasting. Advances in Neural Information Processing Systems, 2023, under review.

<br>

#### **Manuscripts in preparation and to be submitted**
1. Wang, H.; <u><b>Huang, Z.</b></u>*; Yin, G.M.; Bao, Y.; Zhou, X.; Gao, Y. GWRBoost: A geographically weighted gradient boosting method for explainable quantification of spatially-varying relationships. arXiv preprint arXiv:2212.05814, 2022, in preparation and to be submitted.

2. Qi, H.; <u><b>Huang, Z.</b></u>*. Enhancing urban road lighting efficiency through analysis of geospatial big data: A supply-demand matching perspective. Remote Sensing of Environment, 2023, in preparation and to be submitted.

3. <u><b>Huang, Z.</b></u>*; Yin, G.; Bao, Y.; Wang, H.; Zhou, X. Unveiling the inequality and regularity of three-dimensional urban growth in Chinese cities from 2000 to 2020. Nature Cities, 2023, in preparation and to be submitted.

4. Yin, G.; <u><b>Huang, Z.</b></u>*. Examining active mobility behavior through explainable machine learning: Insights from Beijing, China. Transportation Research Part D: Transport and Environment, 2023, in preparation and to be submitted.

5. Zhang, Z.; <u><b>Huang, Z.</b></u>*. Arctic sea ice prediction with AIceNet. IEEE Transactions on Geoscience and Remote Sensing, 2023, in preparation and to be submitted.


#### **Patents**

1. Huang, Z.; Chen, Y.; Gong, X.; Wang, Y.; Liu, Y. A real-time map matching method based on a hybrid parallel computing architecture with GPUs and Spark, 2022, ZL202010338544.4.

2. Yang, L.; Huang, Z. A method for classifying the supply-demand status of urban public transportation at a fine spatial scale based on the travel ratio, 2022, ZL202010794900.3

3. Huang, Z.; Wang, J.; Zhu, R. A parallel traffic simulation method based on traffic clustering, 2022, ZL202110187648.4.

4. Wang, Y.; Huang, Z.; Yin, G.; Yang, L. An evaluation and optimization method for public transport network based on Ollivier-Ricci curvature, 2022, ZL202010460888.2
