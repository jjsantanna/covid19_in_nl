The goal of this Website is to vizualize the information provided by RIVM on COVID-19 cases in the Netherlands. We wrote a crawler for retrieving the information from [https://www.rivm.nl/en/news/current-information-about-novel-coronavirus-covid-19](https://www.rivm.nl/en/news/current-information-about-novel-coronavirus-covid-19) and [https://www.rivm.nl/en/coronavirus-map-netherlands-per-municipality](https://www.rivm.nl/en/coronavirus-map-netherlands-per-municipality). Although RIVM is managing to keep the population aware about the COVID-19 cases, it is lacking to provide a graphical evolution of the cases. *This Website is updated every day around 14:30.* 

We also created a group and a bot on Telegram to update every hour with information. Feel free to join it by clicking [HERE!](https://t.me/joinchat/A8Zq6xTAB8lyg6iZo6_YNA)

### COVID-19 patients per day in the Netherlands
![image](figs/overall_cummulative_stats.png)
The number of deaths and people admitted to hospitals have started growing later than the amount of positive tested people. When this red line starts growing more, the other lines will barely be seen, making it seem as if they are not growing. Therefore, we also show it on a logarithmic scale:
![image](figs/overall_cummulative_stats_logscale.png)

**Important:** RIVM stated that "the actual number of infections with COVID-19 is higher than the number of reports in this update because not everyone suspected of a COVID-19 infection is tested."

### COVID-19 cases per municipality (Gemeente)
This first graph is different from [https://www.rivm.nl/en/coronavirus-map-netherlands-per-municipality](https://www.rivm.nl/en/coronavirus-map-netherlands-per-municipality) because it shows the actual number of cases. The second one is the same as the one from the RIVM. This way, you can see both the actual numbers of infections in your region, but also put those numbers into perspective, by looking at the number of infections per 100.000 inhabitants.

{% include geo_heatmap_actual_numbers.html %}

{% include geo_heatmap_relative_numbers.html %}

### History of COVID-19 cases per municipality
*Unfortunately, the automated crawler started collecting data from 20-03-2020.*

{% include tab_history_per_gemeente.html %}