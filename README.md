# Analyze-the-COVID-19-Mortality-Rate-with-respect-to-Different-Variables
### Examine the relation between the COVID-19 mortality rate and confirmation count, death count, countries and their individual wealth, omicron proportion
-----
*Chenxu Robin Mao | robin.mao@mail.utoronto.ca*

## Summary

To date, the COVID-19 epidemic is still a major global concern. With recent data showing the COVID-19 confirmation toll reaching 671M with the total death roll of 6.83M $^{(1)}$. Different governmental institutions around the globe have brought up various policies to ensure the public health; however, the distortion brought by the virus is irreversible. Thus, with the data provided from Johns Hopkins University, the World Bank and Kaggle, I found it would be meaningful to investigate the relations between the COVID-19 mortality rate and certain variables, including COVID-19 confirmation count, death count, countries and their individual wealth and omicron proportion (terms will be formally defined later).


Throughout this report, the y variable will be the COVID-19 mortality rate. The choice of x variables includes confirm count, death count, countries, omicron proportion varies among the topics and will be introduced in detail and defined in each section. The goal of this report is to find factors that will create significant impacts on the y variable, and analyse their relation if so, or, rephrased as a research question, **"What factors will create significant impacts on the COVID-19 mortality rate?"**

More detailed summaries are given in the the beginning of each section with definition, including *how are they related to the research question, why are they important for the analysis, etc.* 

##### Data source
> COVID-19 Global Confirmation/Death: *https://github.com/CSSEGISandData/COVID-19*

> Global Population: *https://data.worldbank.org/indicator/SP.POP.TOTL*

> COVID-19 Variants: *https://www.kaggle.com/datasets/gpreda/covid19-variants*
