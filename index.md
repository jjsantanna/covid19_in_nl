The goal of this Website is to vizualize the information provided by the National Institute for Public Health and the Environment ([RIVM](https://www.rivm.nl/nieuws/actuele-informatie-over-coronavirus)) on COVID-19 cases in the Netherlands. Although RIVM is keeping the population aware about the cases, there is no graphical visualization of it. This is my contribution to the society. **This Website is updated every day around 15:00.** We also created a group and a bot on Telegram that sends an update every hour with information. Feel free to join it by clicking [HERE!](https://t.me/joinchat/A8Zq6xTAB8lyg6iZo6_YNA)

**Disclaimer:**
[31-03-2020] RIVM stopped sharing the number of positive cases of COVID19 per municipality. Now, the data available is related to the number of hospitalized people per municipality. The source-code and the graphs in this Website were updated reflecting the changes.

<h3 align='center'>COVID-19 patients per day in the Netherlands</h3>

**Important:** The RIVM stated that "the actual number of infections with COVID-19 is higher than the number of reports in this update because not everyone suspected of a COVID-19 infection is tested (anymore)."

{% include overall_cummulative_stats.html max-width="660px" %}

The number of deaths and people admitted to hospitals have started growing later than the number of positive tested people. When this red line starts growing more, the other lines will barely be seen, making it seem as if they are not growing. Therefore, we also show these lines on a logarithmic scale:

{% include overall_cummulative_stats_logarithm.html %}

Thanks to [Joris Trooster](https://www.facebook.com/joris.trooster) suggestion, following you will find the total number of cases vs. the number of confirmed cases. The GREAT explanation of this graph can be found [here](https://www.youtube.com/watch?v=54XLXg4fYsc). A comparison between countries can be found [here](https://aatishb.com/covidtrends).

{% include trajectory_of_cases.html %}

Finally, I don't have access to enough data (and knowledge) to perform a prediction of the spreading of the virus. There is a great "classical infectious disease model calculator" created by [@gabgoh](http://gabgoh.github.io/COVID/). There you can see, based on the literature, how such 'predictions' could be performed. There is also a great interactive visualization by the [New York Times](https://www.nytimes.com/interactive/2020/03/25/opinion/coronavirus-trump-reopen-america.html). Have fun!

<h3 align='center'>Hospitalized People with COVID-19 per municipality</h3>

##### Absolute number of hospitalized people 

{% include geo_heatmap_hospitalized_actual_numbers.html %}

##### (Relative) number of hospitalized people per 100.000 inhabitants.

{% include geo_heatmap_hospitalized_relative_numbers.html %}

This graph shows the same information as the one from [https://www.rivm.nl/actuele-informatie-over-coronavirus](https://www.rivm.nl/actuele-informatie-over-coronavirus)

<!-- <h3 align='center'>History of COVID-19 cases per municipality</h3>

<h4 align='center'>DOUBLE-CLICK THE GEMEENTE YOU WANT TO HIGHLIGHT!</h4>
<h5 align='center'>Then, single-click to compare with others!</h5>
{% include gemeentes.html %} -->

<h3 align='center'>Other projects (that I like) on COVID19 stats</h3>
By [vizualism.nl](https://www.vizualism.nl/meest-getroffen-gemeenten), By [Aatish Bhatia](https://aatishb.com/covidtrends/), By [Johns Hopkins University & Medicide](https://coronavirus.jhu.edu/map.html), by [Worldometers](https://www.worldometers.info/coronavirus/), by [Google](https://google.org/crisisresponse/covid19-map), by [Our world in data](https://ourworldindata.org/grapher/covid-confirmed-cases-since-100th-case), [more to come, or not].

### Acknowledgements
To [RIVM](https://www.rivm.nl/) that provides meaningful information. To [Michelle Peters](https://github.com/Michiexb) who fixed the heatmap graph. To [Erik Kemp](https://www.linkedin.com/in/erikkemp/) who requested meaningful changes to the graphs. To [Wouter Kobes](https://www.linkedin.com/in/wouterkobes/) who reviewed the text. To [Anne Marie]() and [Yuri Engelhardt](https://www.linkedin.com/in/yuriengelhardt/) who provided me additional data.