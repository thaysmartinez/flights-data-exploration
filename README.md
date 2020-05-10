# Flights Data Exploration
## by Thays Martinez


## Dataset

The data is a sample of 498,818 US Flights, occurred during the period of  
1st of January 2015 and 31st of December 2019. It includes flight date,
scheduled departure time, arrival delay, flight outcome (On-time, Cancelled,
or Delayed), taxiing duration and other flight information. The dataset and
feature documentation can be found in the Bureau of Transportation
Statistics [website](https://www.transtats.bts.gov/Fields.asp?Table_ID=236)

## Summary of Findings

In the exploration I found that 80.2% of flights arrived on time, 18.3% were
delayed, and 1.5% were cancelled. The number of flights remained stable during
the first 3 years. 2018 and 2019, however, registered an increase in demand of
nearly 6% when compared 2017. The months of June, July and August recorded
the highest demand, suggesting that summer holidays may be an influence factor.
I also found that the majority of flights are registered between 6am and 10pm,
perhaps due to airports operation times. Its also suggested that the preferred
hours to fly are early in the morning (between 6am and 9am) and at 6pm in the
evening, from when the number of flights starts to ramp down until 11pm.

I concentrated my exploration on delayed flights. 8% of these flights had long
or severe delays, some of which with delays over 24 hours. These strong
outliers, if left in the analysis, would skew the data and are not
representative of the whole dataset. Features that would allow me to verify if
these delays are real are not present in the dataset, therefore I decided to
focus my analysis on short and medium delays.

Finally, I found that ranking airports per average delay would also skew the
analysis due to a few flights with higher delay duration, therefore I changed
the approach and explored the characteristics of flights flying from the 5
busiest airports in the US.

## Key Insights for Presentation

I start the presentation providing context about overall flights' performance in
the 5-year period. The distribution of flights outcomes, flights per arrival
delay duration, and taxi-out/taxi-in duration is plotted with limits applied to
the x-axis to focus on the larger volume of distributions.

Then, I focus the analysis on delayed flights. The relationship between delayed
flights and its reported causes is plotted in a bar chart showing proportions
for each category.

Later, I introduce the arrival delay variable to understand the average arrival
delay per year, month and scheduled departure hour. I plot the distribution of
delay severity levels to demonstrate that the bulk of flights fall into short
and medium delays.

Finally, I analyze the 10 busiest airports per fleet traffic by looking at its
distribution. Its average arrival delay per delay causes is plotted on
violinplots, and its average delay across operation times is plotted on
heatmaps. I conclude the presentation plotting a heatmap of taxi-out average
duration also across operation times.
