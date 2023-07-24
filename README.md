# Cancer_incidence_Scotlands_health_boards


In this project I analysed a dataset containing informations about the cancer incidence in Scotland and in each Scottish health boards, imagining to help inform the planning for provision of cancer treatment services
in the Scottish borders. The dataset contained data from 1997 to 2021.


This was a solo project I worked on as a little task assigned during the week at CodeClan.


## Repository's structure

This repository contains three main parts:

1. a folder called "data" which contains the datasets I decided to use among a list of available data.
2. a .Rmd file called 'cancer_scotland_health_boards_report' which contains the report of the analysis I performed
3. a .R file which contains a dashboard that shows the trend of cancer incidence, in the period considered in the dataset, selecting a specific health board and a specific
cancer specialty.

### Analysis present in the report

1. At first, I analysed the general trend of cancer incidence in the entire Scotland and in each health board.
2. Then I plotted the cancer incidence in the entire scotland distinguishing among the top 10 most common specialty registered.
   - From this plot, I noticed that the top 2 specialties showed a trend which was significantly diffrent with respect of the others.
   - so, I plotted the trend, for each health board, of the top four most common specialties, just for analysing the differnces.
3. Finally, I analysed, for each health board, the number of cancer's incidences depending on sex

For each of these points I provided a specific explanation.

The .R dashboard, has been created using R Shiny. It shows on the left side the general trend of cancer incidence for each health board. This is a static plot,
that should simply be useful to the user to decide which health board he is more interested to analyse.
On the right side, instead, there is the possibility to select a specific health board and a specific cancer specialty among all those in the dataset (not simply the top 10s);
and the plot that appears shows the incidence of that specific cancer type in that specific health board during the period considered in the dataset.

Differently from the report which is finalised to do an analysis of the data, focusing on specific aspects (like selecting the top 10 specialties), 
the dashboard is meant to give a general idea to an interested user  on the general information that the dataset contains.

