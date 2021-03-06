# Belly Button Biodiversity - Plotly Challenge

![belly](https://github.com/UoT-Bootcamp/Plot.ly-Challenge/blob/master/microbes-sem.jpg)

<br>

Click [Belly Button Biodiversity Dashboard](https://uot-bootcamp.github.io/Belly-Button-Biodiversity/) to visit the webpage. <br>

In this assignment, we will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](https://github.com/UoT-Bootcamp/Plot.ly-Challenge/blob/master/data/samples.json), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


* We used the D3 library to read in samples.json.

* Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

  * Use sample_values as the values for the bar chart.
  * Use otu_ids as the labels for the bar chart.
  * Use otu_labels as the hovertext for the chart.

![bar](https://github.com/UoT-Bootcamp/Plot.ly-Challenge/blob/master/Screenshots/bar_chart.png)<br/>

* Created a gauge chart to plot the weekly washing frequency of the individual subject ID.

![gauge](https://github.com/UoT-Bootcamp/Plot.ly-Challenge/blob/master/Screenshots/gauge_chart.png)<br/>

* Created a bubble chart that displays each sample.

  * Use otu_ids for the x values.
  * Use sample_values for the y values.
  * Use sample_values for the marker size.
  * Use otu_ids for the marker colors.
  * Use otu_labels for the text values.

![bubble](https://github.com/UoT-Bootcamp/Plot.ly-Challenge/blob/master/Screenshots/bubble_chart.png)<br/>

* Displayed the sample metadata, i.e., an individual's demographic information.

* Displayed each key-value pair from the metadata JSON object somewhere on the page.

* Updated all of the plots any time that a new sample is selected.

## Final Dashboard:

The final dashboard created by us is below:

![belly](https://github.com/UoT-Bootcamp/Plot.ly-Challenge/blob/master/Screenshots/screenshot3.png)<br/>



