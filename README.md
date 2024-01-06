# Semester Project

Thu Do 

CS625

Due: Monday, December 11 by 11:59pm

## Datasets

*Link to Real Gross Domestic Product Data Source:* https://fred.stlouisfed.org/series/GDPC1

*Link to Federal Funds Interest Rates Data Source:* https://fred.stlouisfed.org/series/FEDFUNDS

*Link to Unemployment Rate Data Source:* https://fred.stlouisfed.org/series/UNRATE

All of the data was obtained from the Federal Reserve Bank of St. Louis's website, which is particularly known for its FRED database containing a wide range of economic time series data. The federal funds interest rate, unemployment rate, and real GDP are key economic indicators that provide insights into an economy's health and performance. 
Real GDP represents the total value of goods and services produced, adjusted for inflation, offering a measure of economic output  on a quarterly basis. The federal funds interest rate, controlled by the central bank, influences borrowing costs and economic activity. 
Lower rates stimulate economic growth, while higher rates can help control inflation. The unemployment rate reveals the percentage of people actively seeking employment within the labor force, offering a snapshot of labor market conditions.
A high unemployment rate may indicate economic distress, while a low unemployment rate may suggest a strong job market.

## Final Question

### **Which 21st-century recession demonstrated the greatest economic impact and the fastest recovery based on real GDP, unemployment rate, and federal funds interest rate?**

## Final Chart

<img src="CS625-Final-Visualization.png" alt="Facet Line Chart Showing COVID-19 Recession: Strongest Impact with Quickest Recovery of the 21st Century">

Link to Final Chart:

[PDF version (Download for Better Quality)](https://github.com/odu-cs625-datavis/fall23-mcw-Thustepsforward/blob/main/CS625-Visualization.pdf)

[PNG version](https://github.com/odu-cs625-datavis/fall23-mcw-Thustepsforward/blob/main/CS625-Final-Visualization.png)

[Chart in Google Colab](https://colab.research.google.com/drive/1Bxi4O7_ar2OLzAm3eXmKXM1LJ-IrwJUT?usp=sharing)

## Idiom: Line Chart

Idiom: Line Chart / Mark: Points connected by Lines
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Months From Beginning of Recovery | key, ordered | horizontal spatial region (x-axis) |
| Real GDP Change From Month Prior to Recession (%) | value, quantitative | vertical spatial region (y-axis) |
| Unemployment Rate (%) | value, quantitative | vertical spatial region (y-axis) |
| Federal Funds Interest Rate (%) | value, quantitative | vertical spatial region (y-axis) |
| Dot-Com, Great, & COVID-19 Recession | value, categorical | color hue |

## How the Final Chart Answers the Question

My facet chart helps the audience determine *which recession had the greatest economic impact* by highlighting the decline or growth of each economic indicator from the start to the end of the recession through changes on the line charts (before the dashed line) as well as the red arrows. The red arrows offer a concise overview of the changes in economic indicators from the beginning to the end of the recession, eliminating the need for the audience to perform any mental calculations based on the y-axis. By using the red arrows, the audience can see that the COVID-19 recession, despite being the shortest of the three, had the most significant impact on real GDP and unemployment rate. 

By examining the changes on the line charts (after the dashed line) and the yellow arrows, the audience can determine that the COVID-19 recession had the *fastest recovery* in terms of length (duration of low interest rates) and recovery rate (considering both unemployment rate & real GDP) compared to the other 21st century recessions. The yellow arrows allow a fair comparison of the recessions' recovery path by highlighting changes from the first month of the recovery period to the 10th, 20th, and 30th month after the recession. One interesting finding was that the GDP recovery rate of the Dot-Com and COVID-19 recessions were very similar to each other. However, the COVID-19 recession had the fastest decline in unemployment rate during the recovery period, making it the quickest recovery among the three recessions. Using the duration of low interest rates as the estimated recovery period (shaded brown area), the audience can see that COVID-19's recovery was the shortest at 21 months, compared to the Dot-Com recession's 30 months and the Great Recession's 76 months.

The headline, "COVID-19 Recession: Strongest Impact with Quickest Recovery of the 21st Century" fits well with the chart by highlighting its purpose and major findings. The headline clearly communicates to the audience that the COVID-19 recession had the strongest economic impact and fastest recovery in the 21st century, hinting at the purpose of the facet chart, which was to compare the economic impact and the recovery path of the 21st century recessions. The subtitle further reinforces the comparison of the recessions by highlighting additional key findings that were previously mentioned.

## Final Thoughts

When picking my topic, I wanted to make sure it aligned with my interests and that there was data readily available. At first, I narrowed it down to employment, specifically the growth or decline of various occupations. I was interested in the topic of employment because career choice is a critical aspect of every individual's life and there was a lot of employment data available on the U.S. Bureau of Labor Statistics' website. After taking a deeper look into the data, I discovered that many of the available data tables about occupations and industries contained a significant overlap in information. While I liked Dr.Weigle's suggestion of examining how well previous employment projections have worked out (2013, projected 2023), I had a difficult time finding the occupation data for 2023 on the U.S. Bureau of Labor Statistics. Therefore, I shifted my focus to comparing the Great Recession and the COVID-19 Recession based on interest rates, unemployment rates, personal savings rates, and US new housing supply rate after a lot of exploratory data analysis. 

To further refine my question, I took Dr.Weigle's suggestion to use a facet chart with the x-axis displaying the beginning of the recessions to easily compare the recessions based on length and time to recovery. In addition to comparing the length of the recession and its recovery, I thought incorporating the unemployment rate and real GDP would also provide some interesting insights into the severity of the recession and its recovery pace. To help estimate the time of recovery, I utilized the federal funds rate as I believe it would be a good indicator since it can provide valuable insights into the overall health of the economy. As I created the facet chart, I thought it would be a better idea to compare all of the 21st-century recessions rather than just the Great Recession and COVID-19 recession.
It took me approximately 10 days to finalize this idea because I changed my topic or question multiple times during the exploratory data analysis phase.

When developing my facet chart, I found myself making the most changes to the y-axis. I wanted each y-axis to have the same range to ensure an accurate representation of the recession's impact and recovery as well as to allow the audience to easily compare the recessions without a lot of mental effort. For instance, I originally displayed real GDP in billions of dollars but found that it may make it challenging for the audience to visualize GDP changes since it may require mental calculations. To address this issue, I opted to display the percentage change in real GDP from the month before the recession to the current month. After completing the facet chart, I used Canva to create a more appealing headline as well as some informative legends and arrows to provide extra context. To my surprise, moving the arrows and their corresponding percentages took about the same amount of time to edit the y-axis. Both edits were tedious and, together, took roughly 5 days. In total, it took about 2 weeks to complete my visualization, with most of the time spent on developing my final question.

## References

1. "Two Recessions, Two Recoveries" : https://www.pewresearch.org/social-trends/2019/12/13/two-recessions-two-recoveries/
2. "Chart Book: Tracking the Recovery From the Pandemic Recession" : https://www.cbpp.org/research/economy/tracking-the-recovery-from-the-pandemic-recession
3. "Chart Book: Tracking the Post-Great Recession Economy" : https://www.cbpp.org/research/economy/tracking-the-post-great-recession-economy
4. "The Great Recession" : https://www.federalreservehistory.org/essays/great-recession-of-200709
5. "Chart Book: Tracking the Recovery From the Pandemic Recession" : https://www.cbpp.org/research/economy/tracking-the-recovery-from-the-pandemic-recession 
