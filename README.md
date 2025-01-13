# Spotify Top 50 Playlist Songs (World chart 2023-2024)

## Introduction 
This project focuses on the ever-evolving music landscape, analysing the flow of songs within the prestigious Spotify Top 50 chart across the globe from 2023 to 2024. By examining both artist and song trends over this dynamic period, we aim to identify valuable insights that shapes the evolving tastes of music listeners worldwide. 

## Objectives
•	Analyse song popularity dynamics. 

•	Investigate artist dominance.  

•	Assess explicit content prevalence. 

•	Compare single vs. album performance. 

•	Visualise trends and develop recommendations. 

## Data Overview 
For this project, the dataset used is gotten from kaggle.com. It contains 27801 rows and 11 columns.

## Tools 
Microsoft Power BI

## Data Preparation
#### **1. Data Cleaning**
• Verified no missing or duplicate entries. 

• Standardised duration_ms to minutes in a new column called duration_minutes.

#### **2. Derived Metrics** 

I used Power BI DAX to calculate the following:

•	**Total artists:** Sum of all unique artists sampled in the chart.

•	**Artist appearances:** Each time an artist appears on the chart.

•	**Average song duration:** Average duration of songs on the chart.

•	**Average popularity score:** Average song popularity score on the chart.

•	**Song appearances:** Each time a song appears on the chart.

•	**Clean songs:** Total number of songs that are not regarded as explicit.

•	**Explicit songs:** Total explicit songs on the chart.

•	**Total albums:** Total number of albums present on the chart.

•	**Total singles:** Total number of single tracks present on the chart.

•	**Total songs:** Total number of songs on the chart.

The report is broken down into three sections, namely Overview, 2023 and 2024 making it a two pages report.

## Analysis 

![Overview](https://github.com/Lawahle/Spotify-top-50-songs-world-chart-2023-2024/blob/main/overview.png?raw=true)


The Overview Page displays a summary of the report featuring key metrics:

•	Total songs: The number of unique songs featured on the Spotify Top 50 chart playlist for 2023-2024.

•	No of Artists: The total number of unique artists featured on the Spotify Top 50 chart playlist for the reporting years.

•	Total Song appearances: The total cumulative number of times all songs appeared on the chart across the reporting years.

•	Artist Domination: The number of times an artist's songs appeared on the chart, indicating their overall chart presence.

•	Explicit and Clean: The proportion (percentage) of explicit and clean songs on the chart.

•	Albums vs Singles: The proportion (percentage) of songs from albums versus singles on the chart.

•	Avg Popularity Score: A trend line showing the fluctuation of average song popularity over the months of 2023 and 2024.

•	Song Domination: A table listing the top songs ranked by their number of appearances on the chart, along with the corresponding artist.

### 2023

![2023](https://github.com/Lawahle/Spotify-top-50-songs-world-chart-2023-2024/blob/main/2023.png?raw=true)

### 2024

![2024](https://github.com/Lawahle/Spotify-top-50-songs-world-chart-2023-2024/blob/main/2024.png?raw=true)


The yearly pages, following the Overview page, provide insights for 2023 and 2024 respectively, displaying the following metrics:

•	Total songs: The number of unique songs featured on the Spotify Top 50 chart playlist for the year.

•	No of Artists: The total number of unique artists featured on the Spotify Top 50 chart playlist for the year.

•	Total Song appearances: The total cumulative number of times all songs appeared on the chart for the year.

•	Avg song duration in minutes: The average duration of songs in minutes on the chart for the year.

•	Avg Position: The average chart position of all songs featured during the year.

•	Artist Domination: The number of times an artist's songs appeared on the chart, indicating their overall chart presence.

•	Explicit and Clean: The proportion (percentage) of explicit and clean songs on the chart for the year.

•	Albums vs Singles: The proportion (percentage) of songs from albums versus singles on the chart for the year.

•	Avg Popularity Score: A trend line showing the fluctuation of average song popularity over the months of the year.

•	Song Domination: A table listing the top songs ranked by their number of appearances on the chart, along with the corresponding artist and year of release.


## Insights and Recommendations

### Observations

From the analysis the below were observed from the Spotify Top 50 Playlist Songs (World 2023-2024).

**1.  Song Turnover:** The significantly higher number of total song appearances (11K in 2023, 16K in 2024) compared to the number of unique songs (423 in both years) indicates a high turnover rate on the Spotify Top 50 chart for both years. This constant flux of songs makes the chart dynamic and highly competitive.

**2. Artist Diversity and Dynamics:** A total of 209 artists were represented in 2023 and 214 in 2024, demonstrating a diverse range of musical talent. While some artists, such as Taylor Swift, The Weeknd, and Arctic Monkeys, maintained a strong presence across both years, new artists like Benson Boone, Chappell Roan, and Sabrina Carpenter emerged and gained significant traction in 2024. This highlights the chart's openness to both established and rising talent.

**3. Explicit Content Preference:** The preference for explicit content remained consistent throughout both 2023 and 2024, with explicit songs holding a slight majority over clean versions. This suggests a continued preference for explicit music among the chart's audience.

**4. Average Popularity Trend:** The average popularity score showed a slight decline towards the end of 2023. This downward trend became more pronounced in 2024, potentially indicating increased competition, shifting audience preferences, or other market factors.

**5. Song Domination:** The "Song Domination" data reveals that both new releases and older hits can achieve and maintain chart presence. This suggests that factors beyond the release year, such as sustained popularity, rediscovery, and effective promotion, play a significant role in a song's chart performance.

### Recommendations

Based on the above observations, below are my recommendations.

**1. Maximize Chart Performance:** Given the high song turnover, artists should prioritize consistent releases rather than relying on a single hit. Strategies should focus on rapidly gaining traction and climbing the charts, including:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Targeted Promotion: Leverage social media, streaming platforms, and radio airplay to generate buzz and enhance visibility.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Fan Engagement: Cultivate a strong online presence and actively engage fans to foster loyalty and drive engagement. Utilize interactive features like polls, quizzes, and behind-the-scenes content to strengthen connections.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Strategic Collaborations: Collaborate with other artists, particularly those with established chart success, to expand reach and attract new audiences.

**2. Cater to Diverse Audiences:** While explicit content currently exhibits a slight preference on the charts, artists should consider releasing clean versions of their songs to broaden their appeal and accommodate a wider audience, thereby potentially increasing reach and expanding their fan base.

**3. Strategic Release Formats:** The balanced representation of albums and singles demonstrates that chart success can be achieved through both formats. Artists and their teams should strategically plan releases, carefully considering the strengths and weaknesses of each format. While singles can generate immediate impact and buzz, albums offer opportunities for deeper storytelling and artistic expression.

**4. Analyze Popularity Trends:** Analyze the average popularity score trends to gain valuable insights into audience behavior. Identifying periods of high and low popularity allows artists and their teams to optimize promotional efforts and timing.

**5. Monitor Chart Performance and Song Dominance:** Continuously monitor chart performance and adjust strategies based on data analysis. Examining the most successful songs provides valuable insights into the elements contributing to chart success, such as genre, production style, and lyrical themes.

**6. Explore Emerging Promotional Channels:** Explore and leverage emerging platforms and promotional strategies, including TikTok, other short-form video platforms, and influencer marketing, to reach new audiences and capitalize on evolving trends.

## Conclusion

The analysis of the Spotify Top 50 chart data for 2023 and 2024 reveals important trends in the music industry.

There is a high turnover of songs, with many songs appearing and leaving the chart quickly. Artists need to release music regularly and use effective strategies to gain popularity and not just rely on one single hit. The chart includes a mix of both well-known and new artists. While some established musicians stay prominent, many new talents also find success, highlighting the chart's welcoming nature for all types of artists.

Older songs often remain popular and perform well on the chart, showing that past hits can achieve lasting success with continued promotion. There is also a strong preference for explicit content, which tends to do better; however, artists should consider making clean versions for wider appeal.

To be successful, artists should consistently release new music, promote it actively, engage with fans, use data to inform decisions, collaborate with other artists, adapt to trends, and plan their releases thoughtfully. The Spotify Top 50 chart is a challenging and fast-paced environment that demands innovation and strategic thinking from artists.



