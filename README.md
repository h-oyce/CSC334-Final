# Temporal Analysis of Autism Prevalence

Juniper Huang

[Slide Show Presentation](https://www.canva.com/design/DAGD6m__i6k/a8hojphq5l0y8W5wElnJBQ/edit?utm_content=DAGD6m__i6k&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Data

[Autism Prevalence Data](https://www.cdc.gov/ncbddd/autism/data/autism-data-table.html)

[All Countries ISO Codes](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv)

## Summary

The data analysis is conducted in Python using the Pandas and Plotly packages. To create the choropleth maps, [this tutorial](https://plotly.com/python/choropleth-maps/) was followed. I first uploaded both datasets to the file and trimmed it down to the columns I wanted to focus on. To use the function px.choropleth, it required counties to be labeled as their ISO country codes. Since the United States and the United Kingdom did not have their official names in the original "Countries" column, I had to change them manually and then change all countries to their ISO codes. Additionally, I then created a new column named "Year Range" so that the faceted rows could be used in the later visualization. 

## Results



## Ethical Concerns

1. **Representation**: Many of the studies were performed in Western countries and had a strong bias to diagnose boys under the age of 18.
2. **Stigma and potential harm**: While autism is more well understood today, this was not always the case. Some of the events discussed are strong reminders of the history of intense ableism.

## Future Work


