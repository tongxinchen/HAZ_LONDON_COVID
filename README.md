# Sensing Dynamic Human Activity Zones using Geo-tagged Big Data in Greater London, UK during the COVID-19 Pandemic 

## Table of Contents 
- [Citation](#citation)
- [Project intrduction](#intrduction)
- [Notebook usage](#usage)
- [Open data](#data)
- [Acknowledgements](#ack)

<!-- Citation -->
## Citation

If you use the functions in this project in your research, please cite this source:

```

citation


```


<!-- Project intrduction -->
## Project intrduction

Exploration of dynamic human activity gives significant insights into understanding the urban environment and can help to reinforce scientific urban management strategies. Lots of studies are arising regarding the significant human activity changes in global metropolises and regions affected by COVID-19 containment policies. However, the variations of human activity dynamic amid different phases divided by the non-pharmaceutical intervention policies (e.g., stay-at-home, lockdown) have not been investigated across urban areas in space and time and discussed with the urban characteristic determinants. In this study, we aim to explore the influence of different restriction phases on dynamic human activity through sensing human activity zones
(HAZs) and their dominated urban characteristics. Herein, we proposed an explainable analysis framework to explore the HAZ variations consisting of three parts, i.e., footfall detection, HAZs delineation and the identification of relationships between urban characteristics and HAZs. In our study area of Greater London, United Kingdom, we first utilised the footfall detection method to extract human activity metrics (footfalls) counted by visits/stays at space and time from the anonymous mobile phone GPS trajectories. Then, we characterised HAZs based on the homogeneity of daily human footfalls at census output areas (OAs) during the predefined restriction phases in the UK. Lastly, we examined the feature importance of explanatory variables as the metric of the relationship between human activity and urban characteristics using machine learning classifiers. The results show that dynamic human activity not only exhibits statistically significant differences in terms of the HAZ distributions across restriction phases but is strongly associated with urban characteristics (e.g., specific land use types) during the COVID-19 pandemic. These findings can improve the understanding of the variation of human activity patterns during the pandemic and offer insights into city management resource allocation in urban areas concerning dynamic human activity.



<!-- Notebook usage -->
## Notebook usage

Our data in this project are all in notebook file ```HAZ_analysis.ipynb``` consitting of  1) HAZ Clustering; 2) HAZ Delineation; 3) Relationships between HAZs and static urabn characteristics. 

All codes can be excuted in conda environment with the installed pkgs listed at the top of this notenook. 

<!-- Open data -->
## Open data

All sample data and our generated result data are in ```data```  folder.

<!-- Acknowledgements -->
## Acknowledgements

