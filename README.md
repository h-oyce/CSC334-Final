# Temporal Analysis of Autism Prevalence

Juniper Huang

[Slide Show Presentation](https://www.canva.com/design/DAGD6m__i6k/a8hojphq5l0y8W5wElnJBQ/edit?utm_content=DAGD6m__i6k&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Data

[Autism Prevalence Data](https://www.cdc.gov/ncbddd/autism/data/autism-data-table.html)

[All Countries ISO Codes](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv)

[Significant Events in Autism Research and Awareness](https://github.com/h-oyce/CSC334-Final/blob/main/Events.csv)

## Summary

The data analysis is conducted in Python using the Pandas and Plotly packages. To create the choropleth maps, [this tutorial](https://plotly.com/python/choropleth-maps/) was followed. I first uploaded both datasets to the file and trimmed it down to the columns I wanted to focus on. To use the function px.choropleth, it required counties to be labeled as their ISO country codes. Since the United States and the United Kingdom did not have their official names in the original "Countries" column, I had to change them manually and then change all countries to their ISO codes. Additionally, I then created a new column named "Year Range" so that the faceted rows could be used in the later visualization. 

## Results

Overall, the prevalence of autism across the world increased as time progressed. From the visualization, the largest spike in prevalence occurred between 2000-2005 and 2005-2010, with every 5-year choropleth map after 2010 also having a large increase in prevalence rates. Additionally, there are many countries that had their first published prevalence studies after 2005, such as China, India, Brazil, Nigeria, and Saudi Arabia. A majority of the countries that had their first prevalence studies published after 2005 were located in Asia, Africa, and South America. When these countries did have published prevalence rates, they were significantly lower than North American and European countries' published rates. This may be due to disparities in resources for diagnosis, in autism awareness, or in cultural acceptance of autism. 

## Ethical Concerns

1. **Representation**: Many of the studies were performed in Western countries and had a strong bias to diagnose boys under the age of 18.
2. **Stigma and potential harm**: While autism is more well understood today, this was not always the case. Some of the events discussed are strong reminders of the history of eugenics and intense ableism. While this is not representative of how autism is thought of today, they are still part of its history. The potential for harm in discussing these events is still very possible so I hope they will be discussed carefully. 

## Future Work

1. In future interactions, I would try to incorporate the [Shiny package](https://shiny.posit.co/py/docs/install-create-run.html#install) to allow for more control over the printing of the choropleth maps. As the code is currently written, the faceted maps are difficult to read and interpret due to their small size. I got the suggestion from Professor Jordan Crouser during our presentation day, but I struggled to integrate it myself. 
2. In the [Events.csv](https://github.com/h-oyce/CSC334-Final/blob/main/Events.csv), I began to compile significant events and milestones in autism research, awareness, and the community as a whole. Unfortunately, there is a bias towards American events due to the more accessible documentation. If this dataset was further expanded upon, I hope to use these events as points of comparison to the prevalence data in the future to answer questions such as "What historical events had the greatest impact on autism prevalence? Who benefits most from raising awareness of autism? How does autism research's ableist past affect modern research?" 
