# Data Visualisation Deconstruction & Reconstruction Using R

# Background
There are some problematic data visualisations on the web which have multiple issues that we can fix or improve. This project aims to identify the problematic data visualisation on the web and utilise the visual presentation of the data by using R. 
## historical_emissions.csv
- All the outcomes are based on this data set
## Data Visualisation Deconstruct.Rmd
- Demonstrates the whole process of this project
## Output.htm
- Present the whole report 

<img src="https://github.com/BlackOak8/Data-Visualisation-Deconstruction-Reconstruction/blob/Synthetic-Data(Data-Preprocessing-%26-Summary-Statistics)/Original%20Visual.png" alt="Source: World Resources Institute (2023)">
Source: World Resources Institute (2023)

# Deconstruct
## Objective

The original data visualisation was published in the article entitled 'This Interactive Chart Shows Changes in the World's Top 10 Emitters', which appeared in the publication of the World Resources Institute, Insights. For the purpose of combating the climate change, many different countries have come together and joined the agreement to decrease greenhouse gas emissions.

According to the original article, the objective of original data visualisation is therefore to provide the complete picture of the worldwide greenhouse gas emission, by displaying the distribution of greenhouse gas emissions by country and associated economic sectors and shows the changes of these top emitters over recent years.

For instances, the colour hue is implemented to represent the legend of top ten emitters, the authors of the article urge the most significant emitters to implement measures to reduce greenhouse gas emissions.

## Audience

In order to identify the target audiences, we first need know more about publishing platform, the World Resources Institute. In contrast to news or other form of medias, the World Resources Institute seeks to form strategic alliances with national governments, businesses, and non-governmental organisations. (Supporting Country-led Transitions, 2023) Therefore, the target audiences should be organisations or individuals with an interest in the issue of climate change.

## Critique

The visualisation chosen had the following three main issues:

### Visual bombardment:
* While the figure is an interactive three-layer doughnut chart entitled 'The Top 10 GHG Emitters Contribute Over Two-Thirds of Global Emissions', it is initially unclear to readers which of the layers represents which information. To gain a deeper comprehension of the figure, it is necessary to read from the inner layer to the outer layer, from the top ten emitters to the countries and then to the emissions categories. Furthermore,the small proportions of outer layer on the left hand side are hard to differentiate and label that provide uninformative detail. This may have caused confusion for readers who require more time to digest the representation of the figure.

### Perceptual issues:
* The drawback of doughnut chart only allows for the visualization of proportions within different categories. However, this approach does not facilitate the examination of how emissions evolve over time. This means the figure could not fulfill the aim of demonstrating the changes of these top emitters over recent years. Moreover, a comparison of greenhouse gas emissions by country reveals a significant degree of overlap among Canada, Saudi Arabia, South Korea, and Mexico. This observation gives raise to the question of whether there are additional countries that contribute a substantial amount of greenhouse gases, in addition to the ten countries with the highest emissions.

### Readability issues:
* The legend colour of the country are duplicated, for instances, China and Canada, India and Indonesia, EU(27) and Iran. In addition, the legend color of Manufacturing/Construction sector in China is distinct from the rest. These issues might result in confusion when interpreting different segments in the figure. Furthermore, the lack of uniformity in font size within the outer layer increases the challenge of readability.

# Reconstruct
The following plot fixes the main issues in the original.

<img src="https://github.com/BlackOak8/Data-Visualisation-Deconstruction-Reconstruction/blob/Synthetic-Data(Data-Preprocessing-%26-Summary-Statistics)/Reconstruct.png" alt="Source">

# References

* Friedrich, J., Ge, M., Pickens, A., & Vigna, L. (2023). *This Interactive Chart Shows Changes in the World’s Top 10 Emitters*. Retrieved September 16, 2024, from World Resources Institute website: https://www.wri.org/insights/interactive-chart-shows-changes-worlds-top-10-emitters

* Climate Watch (n.d.) *Climate Watch Historical Country Greenhouse Gas Emissions Data*. Retrieved September 16, 2024, from Climate Watch website: https://www.climatewatchdata.org/ghg-emissions?end_year=2021&start_year=1990
