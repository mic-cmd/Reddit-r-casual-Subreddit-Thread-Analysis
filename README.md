# Reddit-r-casual-Subreddit-Thread-Analysis
![Alt text](https://blog.distart.de/reddit-marketing)
**Introduction**

In the dynamic landscape of social media marketing, understanding the performance of various content categories is pivotal for optimizing strategies and enhancing client engagement. This report presents a comprehensive analysis conducted on the Reddit r/CasualUK subreddit data, aimed at evaluating the performance of different post categories. The insights derived from this analysis will aid in formulating data-driven recommendations to boost client reach and engagement effectively.

The primary objectives of this project are to:
	1.	Increase Client Reach and Engagement: Enhance the visibility and interaction levels of client posts across social media platforms.
	2.	Gain Valuable Insights: Extract actionable insights from data to inform and refine social media strategies.
	3.	Achieve Social Media Goals: Assist clients in meeting their specific social media objectives through informed recommendations and strategies.

**Project Scenario**

Operating within a social media marketing agency, the focus of this project is to analyze and report on the performance of different categories of posts within the r/CasualUK subreddit. By categorizing posts into distinct themes such as fitness, tech, family, and beauty, the analysis aims to identify patterns and trends that can inform strategies to optimize social media performance for clients. Python was utilized for data extraction, cleaning, analysis, and visualization to ensure a streamlined and reproducible workflow.

**Data Source**

The dataset comprises threads from the Reddit r/CasualUK subreddit, encompassing various post attributes such as thread_id, author, num_comments, score, selftext, upvote_ratio, and created_utc, among others.

**Data Cleaning**

To ensure data integrity, duplicate entries based on the selftext column were identified and removed, retaining only the first occurrence of each unique post. Rows with missing (NaN) or empty selftext fields were excluded from the analysis to maintain the quality and relevance of the dataset.

**Data Categorization**

Posts were categorized into four main themes: Fitness, Tech, Family, and Beauty. Each category was associated with a comprehensive list of keywords to facilitate accurate classification based on the content of the selftext field.


**Findings:**
Categories with higher upvote ratios reflect more positively received posts. Fitness and Tech related posts appear to be more popular among the subreddit users. These two categories receives the highest number of comments and upvotes. Afternoon (11:00 - 18:00) has the highest median number of comments, suggesting the best time to post followed by morning (00:00 - 10:00). There is a positive correlation between the number of comments and the score, suggesting that posts with more comments tend to have higher scores. Although the connection is not strong enough,  but it appears that posts reflecting negative sentiments receive more engagements(comments) from users.


**Conclusion**

The analysis of the r/CasualUK subreddit data has yielded valuable insights into the performance of different post categories, optimal posting times, and the impact of content characteristics on engagement metrics. Key findings indicate that tech and fitness categories outperform others in terms of both score and number of comments, and although small, sentiment play a role in driving engagement.

**Recommendations**
Allocate more resources and create more content within categories that exhibit higher average scores and comment counts, such as: Fitness and Tech. Schedule posts during the time of day that correlates with higher engagement. Encourage discussions and interactions within posts by posing questions, creating polls, or inviting user opinions to boost comments.
