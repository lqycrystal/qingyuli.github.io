---
title: "Deep learning-based framework for city-scale rooftop solar potential estimation by considering roof superstructures."
excerpt: "The open-source code is used for estimating rooftop solar potential."
collection: software
---
<img src='https://lqycrystal.github.io/qingyuli.github.io/images/solarnet.png'><br/>


## Installation
You can get the code from [GitHub](https://github.com/lqycrystal/SolarNet_plus)
We propose a novel framework, SolarNet+, for rooftop solar potential analysis. The input aerial image is fed into a CNN to learn roof orientation and superstructure maps. Based on the predicted roof orientation map, individual classes of roof segments (i.e., Flat, west (W), south (S), east (E), and north (N)) are extracted, and their roof area available for solar panel installation is derived by excluding the area of superstructures, which is determined using the predicted roof superstructure map. The yearly generated energy per solar panel can be obtained from a solar radiation database for each roof segment category. Next, this value is multiplied by the maximum number of solar panels installed on roof segments. Ultimately, the overall rooftop solar potential is calculated by aggregating the potential across all categories of roof segments.


## Citations

Li, Qingyu, Sebastian Krapf, Lichao Mou, Yilei Shi, and Xiao Xiang Zhu. "Deep learning-based framework for city-scale rooftop solar potential estimation by considering roof superstructures." Applied Energy 374 (2024): 123839.
