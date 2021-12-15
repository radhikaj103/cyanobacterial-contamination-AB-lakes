# Careful about which lakes you swim in!

## Introduction
Cyanobacteria are photosynthetic microorganisms that occur on the surface of most inland water bodies. Although commonly known as blue-green algae because of their photosynthetic nature, they are not related to other algae and can significantly impact the quality of the water and the aquatic ecosystem ("Blue-green algae". Encyclopedia Britannica, 2017). These bacteria can form harmful blooms under favorable temperature and nutrient conditions producing unpleasant odors and tastes and sometimes toxic compounds posing a potential health risk (Alberta Health Environmental Public Health Science Team, 2021). Skin contact with these bacteria can cause allergic reactions, and infections at levels exceeding 20,000 cells/ml (World Health Organization, 2003, p. Excutive summary xxvii). Ingestion of their toxins can cause a range of systemic symptoms, including hepatotoxic or neurotoxic effects, and even death (Alberta Health Environmental Public Health Science Team, 2021).

In Alberta, cyanobacteria awareness has increased amongst health agencies and the general public in the last two decades. Alberta health services and beach operators closely monitor the numbers of cyanobacteria species in high-use recreational beaches between June and September. They collect samples from the water bodies and submit them for analysis of cyanobacterial bloom indicators. These data, along with some visual metrics of water quality, are used to assess water safety and issue appropriate water use advisories (Alberta Health Environmental Public Health Science Team, 2021).

In this project, we propose to investigate whether cyanobacterial blooms are prevalent in Alberta's recreational beach waters and which factors might contribute to their growth during the summer months using data collected between 2014 and 2021.

## Guiding questions
We propose to answer the following questions through appropriate analyses of the datasets presented in the next section.

- Which quantitative paramater efficiently represents the extent of cyanobacterial contamination in Alberta's lakes and can be used as the response variable for the level of contamination?

- How have the levels of cyanobacterial contamination increased over the years?

	- We aim to perform time-series analysis of cyanobacterial cell counts and other quantitative parameters indicative of cyanobacterial contamination in Alberta’s recreational waters between 2014 and 2020 to answer this question.
	- Check for trends in a monthly & annual analysis , are there certain months/Years where counts are higher and why?
	- 2021 Data was not utilized due to incompleteness and collection authority recommendation.

- What is the correlation between the cyanobacterial counts and the water temperature in a given area?

	- Cyanobacteria are becoming increasingly dominant worldwide as the climate continually changes due to rising global temperatures. Cyanobacteria thrive in warm waters. We propose to test this hypothesis empirically using the datasets.

- How helpful are turbidity and colour of the water to predict the level of cyanobacterial contamination?

	- Is there any and how accurate are turbidity and colour,in predicting the response variable (statistical significance)?

- What impact does the geographical location of the water body have on the level of contamination (urban vs remote locations)

	- As the lakes in urban areas are expected to be more polluted than the ones in remote locations, we plan to investigate the geospatial variation of the cyanobacterial cell counts using the geospatial data associated with the water bodies.

## Dataset:
The data set used in our project is part of the Alberta government open data source, thus is free to use to the public. Our group is utilizing the following data set:

Cyanobacterial blooms in Alberta recreational waters.csv. This Dataset was collected by Alberta Health Environmental Public Health Science Team (2014-2021). https://open.alberta.ca/dataset/cyanobacterial-blooms-in-alberta-recreational-waters#summary

The data set comes in an Excel file with 18 columns as variables, and 2687 rows as observations. The data is not structured in hierarchies.

## References:

- Alberta Government. Open Government License [Online]. Available at: https://open.alberta.ca/licence (Accessed 27 September 2021)

- Alberta Health Environmental Public Health Science Team (2021). Cyanobacterial blooms in Alberta recreational waters [Online]. Available at: https://open.alberta.ca/opendata/cyanobacterial-blooms-in-alberta-recreational-waters (Accessed 27 September 2021)

- Britannica, The Editors of Encyclopaedia. "Blue-green algae". Encyclopedia Britannica, 29 Dec. 2017, [Online]. Available at: https://www.britannica.com/science/blue-green-algae (Accessed 10 October 2021)

- Massey, Isaac Yaw, Wu, Pian, Wei, Jia, Luo, Jiayou, et al. (2020) ‘A Mini-Review on Detection Methods of Microcystins’, Toxins, MDPI AG, 12(10), p. 641, [online]. Available from: http://dx.doi.org/10.3390/toxins12100641 (Accessed 19 October 2021)

- Municipal Boundaries by Altalis [Online]. Available at: https://www.altalis.com/map;id=113 (Accessed 7 October 2021)

- Quesada A., Vincent W.F. (2012) Cyanobacteria in the Cryosphere: Snow, Ice and Extreme Cold. In: Whitton B. (eds) Ecology of Cyanobacteria II. Springer, Dordrecht. Available at: https://doi.org/10.1007/978-94-007-3855-3_14 (Accessed 19 October 2021)

- Rantala, Rajaniemi-Wacklin et al. (2006) 'Detection of microcystin-producing cyanobacteria in Finnish lakes with genus-specific microcystin synthetase gene E (mcyE) PCR and associations with environmental Factors'. Applied and Environmental Microbiology, 72(9), p.6101 [Online]. Available at: https://journals.asm.org/doi/10.1128/AEM.01058-06 (Accessed 17 October 2021)

- Stewart, R (2018). GeoPandas 101: Plot any data with a latitude and longitude on a map [Online]. Available at: https://towardsdatascience.com/geopandas-101-plot-any-data-with-a-latitude-and-longitude-on-a-map-98e01944b972 (Accessed 27 September 2021)

- World Health Organization, Eds: Ingrid Chorus and Jamie Bartram (1999). Toxic Cyanobacteria in Water: A Guide to Their Public Health Consequences, Monitoring, and Management [Online]. Available at: https://www.who.int/water_sanitation_health/resourcesquality/toxcyanbegin.pdf (Accessed 27 September 2021)

- World Health Organization (2003). Guidelines for Safe Recreational Water Environments, Volume 1: Coastal and Fresh Waters. [Online]. Available at: http://apps.who.int/iris/bitstream/handle/10665/42591/9241545801.pdf?sequence=1 (Accessed 27 September 2021)