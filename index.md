The goal of this Website is to vizualize the information provided by the National Institute for Public Health and the Environment ([RIVM](https://www.rivm.nl/nieuws/actuele-informatie-over-coronavirus)) on COVID-19 cases in the Netherlands. Although RIVM is keeping the population aware about the cases, there is no graphical visualization of it. This is my contribution to the society. **This Website is updated every day around 15:00.** We also created a group and a bot on Telegram that sends an update every hour with information. Feel free to join it by clicking [HERE!](https://t.me/joinchat/A8Zq6xTAB8lyg6iZo6_YNA)

### COVID-19 patients per day in the Netherlands

**Important:** The RIVM stated that "the actual number of infections with COVID-19 is higher than the number of reports in this update because not everyone suspected of a COVID-19 infection is tested (anymore)."

{% include overall_cummulative_stats.html max-width="660px" %}

The number of deaths and people admitted to hospitals have started growing later than the number of positive tested people. When this red line starts growing more, the other lines will barely be seen, making it seem as if they are not growing. Therefore, we also show these lines on a logarithmic scale:

{% include overall_cummulative_stats_logarithm.html %}


### COVID-19 cases per municipality (Gemeente)

##### Absolute number of cases 

{% include geo_heatmap_actual_numbers.html %}

##### (Relative) number of cases per 100.000 inhabitants.

{% include geo_heatmap_relative_numbers.html %}

This graph shows the same information as the one from [https://www.rivm.nl/en/coronavirus-map-netherlands-per-municipality](https://www.rivm.nl/en/coronavirus-map-netherlands-per-municipality)

### History of COVID-19 cases per municipality
*Unfortunately, the automated crawler started collecting data from 20-03-2020 onwards.*

{% include tab_history_per_gemeente.html %}

### Other projects (that I like) related to COVID-19 worldwide
By [Johns Hopkins University & Medicide](https://coronavirus.jhu.edu/map.html), by [Worldometers](https://www.worldometers.info/coronavirus/), by [Google](https://google.org/crisisresponse/covid19-map), by [Our world in data](https://ourworldindata.org/grapher/covid-confirmed-cases-since-100th-case), [more to come, or not].

### Acknowledgements
To [RIVM](https://www.rivm.nl/) that provides meaningful information. To [Michelle Petters](https://github.com/Michiexb) who fixed the heatmap graph. To [Erik Kemp](https://www.linkedin.com/in/erikkemp/) who requested meaningful changes to the graphs. To [Wouter Kobes](https://www.linkedin.com/in/wouterkobes/) who reviewed the text. To [Anne Marie]() and [Yuri Engelhardt](https://www.linkedin.com/in/yuriengelhardt/) who provided me additional data.