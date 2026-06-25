data - contains the csv used in the project (SleepStudy.csv)

report - contains the rmd and html files of the R file used to create the graphs
also contains the report analysis in a PDF file named Kohl_Report_Analysis

this analysis uses the tidyverse and plotly packages, with those installed run all of the chunks in order
to get see the graphs. 

The R Markdown script generates the following graphs:
- Average Sleep Distribution: A histogram checking the normality of student sleep hours.
- Average Sleep vs. GPA: An **interactable** scatter plot with trend lines evaluating if more sleep correlates with a higher GPA across different class years.
- GPA vs. Sleep Type: A boxplot comparing academic performance between "Larks" (early birds) and "Owls" (night owls).
- Mental Health Impact: Two regression scatter plots mapping how both sleep quality and sleep duration affect overall depression scores.
- Lifestyle Factors: A scatter plot exploring the relationship between weekly drinking rates, categorical alcohol use, and happiness.

After reviewing the charts and what I wanted to show I decided to redesign my Average Sleep vs GPA chart, as this was the most important chartfor my analysis and dataset overall. I changed the color pallete to make it color-blind friendly, redesigned it and added an overall trend line, and made it interactable to make it easy to single out each class year's data or just the overall.

Here is the old chart:

<img src="https://raw.githubusercontent.com/JoeKohl/dataviz_final_project/main/figures/oldChart_1.png" width="70%" height="70%">

Here is the updated chart:

<img src="https://raw.githubusercontent.com/JoeKohl/dataviz_final_project/main/figures/redesign_1.png" width="70%" height="70%">
