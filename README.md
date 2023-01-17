# 2020 F1 Data Visualization


## Abstract

An assignment from a graduate level course in R focused on data manipulation and visualization. Raw data was collected from the 2020 Formula 1 racing season was downloaded from ergast.com as a large JSON file containing information from all 17 race results in the 2020 season. For details on how the race results are reported in the data see the [race result page](https://ergast.com/mrd/methods/results/) on Ergast. Data was read into R using the `jsonlite` packages and formatted following best "tidy" data practices. The results are displayed in a compelling visualization for drivers and constructors that can be viewed using the following [link](https://andrewamore.github.io/F1-2020-Visualization/).

## Documents of Interest

- `index.html`: Output file displaying the code, tables and figure.
- `proj1.Rmd`: Code used to generate `index.html` displaying the visualization.
- `./data/get_data.R`: Data harvesting script.
