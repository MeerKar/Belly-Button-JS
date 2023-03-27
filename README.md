# Belly-Button-JS

### Background

In this assignment, an interactive dashboard is built to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


<img width="1091" alt="image" src="https://user-images.githubusercontent.com/116701851/227360206-adf62b37-8a73-4302-b785-f42ba26f2286.png">

THe link to the dashboard is as follows. file:///Users/meeragnair/Desktop/JS%20/Belly-Button-JS/Starter_Code%203/StarterCode/index.html



1.  For this the D3 library is used to read in "samples.json" from the URL "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json".

<img width="410" alt="image" src="https://user-images.githubusercontent.com/116701851/227072115-2ce9ec05-fdf1-4b15-b2cc-b9322c9d712f.png">
 and the link follows https://github.com/MeerKar/Belly-Button-JS/blob/main/Starter_Code%203/StarterCode/static/js/app.js
 
 
 
2.  Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Using sample_values and otu_ids as the values and labels for the bar chart and 

Use otu_labels as the hovertext for the chart.

<img width="338" alt="image" src="https://user-images.githubusercontent.com/116701851/227072472-1709218b-1c07-4256-ae5b-395684c2336f.png">

3.  Created a bubble chart to displays each sample.

Using otu_ids for the x values.

Using sample_values for the y values.

Using sample_values for the marker size.

Using otu_ids for the marker colors.

Using otu_labels for the text values.

<img width="881" alt="image" src="https://user-images.githubusercontent.com/116701851/227072775-360308ed-a3aa-497a-b549-a15133aa132d.png">


4.  The sample metadata, i.e., an individual's demographic information is displayed.

 5.  And each key-value pair from the metadata JSON object somewhere on the page is also displayed.

<img width="179" alt="image" src="https://user-images.githubusercontent.com/116701851/227073108-0dc04af6-04a5-4418-a321-e8298ffd068e.png">

6. And Finally updated all the plots when a new sample is selected.An example dashboard is shown as follows:

<img width="1050" alt="image" src="https://user-images.githubusercontent.com/116701851/227073481-8ba02920-e0dc-4cc5-a526-a2ee1153a10f.png">


