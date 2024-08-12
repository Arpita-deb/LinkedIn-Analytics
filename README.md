# LinkedIn-Analytics
![Purple Minimalist Brush Personal LinkedIn Banner (2)](https://github.com/user-attachments/assets/c23860f8-bd54-4845-9cc8-803d02dbd5c7)

## Introduction:

I’ve been using LinkedIn for three years, but only recently I started sharing regular contents on Data Analytics. Curious about my activity, I decided to analyze my LinkedIn data and create a story with Power BI. To my surprise, this quick analysis revealed some fascinating insights.

Here's a short presentation slide, highlighting the key insights: [Linkedin Analytics.pdf](https://github.com/user-attachments/files/16582549/Linkedin.Analytics.pdf)

## Objectives:

The key questions I wanted to find answers of are -

1. How has my network grown since I started regularly posting data analysis content?
2. Are there changes in viewer engagement on a yearly, monthly, or weekly basis? What caused them?
3. Is there a link between post engagement (likes, comments) and post impressions?
4. How can I use this data to decide the best times and types of posts for higher engagement?

## Steps Taken:

### 1. Collecting Data:
I exported my LinkedIn analytics from August 1st, 2023, to August 8th, 2024. This data included follower counts, post views, and engagement metrics.

* **Data Description:**




## 2. Cleaning and Organizing Data:
Using Power Query I handled missing values, changed datatypes and column headers and transformed the data formatting. I also joined tables and added new columns. Using M-code, I created a Date Table to extract month, weekday, week number, and year information.

This is how the data is structured in Power BI.

## 3. Identifying Metrics:

- Followers:
- Connections:
- Posts: The contents one shares on Linkedin. Can be images, videos, articles, documents, links etc.
- Engagements: Once a content is posted, people engage with them through likes, comments, shares/reposts.
- Impressions: It is the number of times the contents been displayed on users’ screens regardless their interaction with them.

So, the main metrics I'll look into are the - 

* Total Count of Connections and Followers
* Change in number of Posts, Engagements, and Impressions 
* Yearly, Monthly and Weekly distribution of Posts and Engagements

## 4. Exploring the Data:
Using Power BI visuals, I explored the data and created DAX measures for total impressions, engagements, and the number of posts. I kept all measures in a separate table from the original data, for ease of use.

## 5. Results:

**1. How has my network grown since I started regularly posting data analysis content?**

![1](https://github.com/user-attachments/assets/7585334e-2bd1-48d1-bc77-361e3a948a78)

![2](https://github.com/user-attachments/assets/cf7eecff-c853-46d0-ad76-ce73028443d5)

- In 2024, I posted 35 times, compared to 11 times in 2023, a 218% or 2- fold increase.
- Post impressions soared by 1042% from 2023 to 2024, a 10-fold jump.
- My followers grew by 805%, nearly eight times more than last year.

However, there’s a discrepancy between the present LinkedIn follower count (784) and the data (969). Possible reasons include:

- LinkedIn data may be from a different period.
- Some followers might have become inactive or deleted their accounts after the data was collected.
- There may have been follower loss since the last update.
- I used the later data since it can be aggregated by dates, years and months and the % change can be calculated.

**2. Are there changes in viewer engagement on a yearly, monthly, or weekly basis? What caused them?**

![3](https://github.com/user-attachments/assets/dc43e7f5-ad50-4d75-b068-998cc0069eb9)
This timeline chart shows daily engagement from August 2023 to August 2024. Engagement was low throughout 2023 but surged between May and July 2024, coinciding with my virtual internships when I posted several data analysis reports.

There has been overall 1516 % increase in engagements from 2023 to 2024.

Majority of the spikes corresponds to my posts, which is expected. The most significant spike was on June 7th, with 121 engagements following the publication of my AdventureWorks sales analysis report.
![6](https://github.com/user-attachments/assets/c631ead3-b4d3-4472-bfef-28f02edcf30d)

These spikes also indicate that the engagement rate drops steeply only a day after the post. This highlights the immediate impact of high-quality content but also shows that maintaining engagement requires consistent and strategic content planning.

![4](https://github.com/user-attachments/assets/b43e1050-d1a3-4dd6-b03c-383d80abf1e9)
Out of 67K impressions about 58K are made between May and July.

**3. Is there a link between post engagement (likes, comments) and post impressions?**
![7](https://github.com/user-attachments/assets/e0d36248-833d-495a-9c94-fac1abeaafd7)
Each bubble represents a post, with larger bubbles having higher number of likes.
I assumed posts with the highest impressions would also have the most engagement. This scatterplot shows that as a post gets higher impressions, the number of engagements (e.g., shares, likes, and comments) also increases.
![8](https://github.com/user-attachments/assets/c9d03334-76e9-42c2-8eba-9c3ee59967f3)
The blue bubbles show the high performing posts.

**4. How can I use this data to decide the best times and types of posts for higher engagement?**

![5](https://github.com/user-attachments/assets/79522e95-75ad-4382-9574-b6050a27cdac)

A chart comparing posts and engagement across weekdays shows that while I mainly post on Tuesdays, Fridays see the highest engagement, followed by Tuesday and Wednesday. Weekends have the lowest engagement.

This chart reveals the importance of timing posts to align with audience activity.

![9](https://github.com/user-attachments/assets/3c0527d3-3263-4825-aec4-ab7f9c475e27)

I’ve been posting an average of 0.87 posts per week, just under one post weekly. However, I posted slightly more this year than last year. To increase engagement and visibility, I need to post more frequently.

## Summary of the Key Findings:

* I posted 35 times in 2024, compared to 11 times in 2023 (218% increase from 2023).
* Post impressions skyrocketed by 1042% from 2023 to 2024, showing a 10-fold increase.
* My followers grew by 805%, nearly eight times more than the previous year.
* Even though I mostly post on Tuesdays, people engage more on Fridays.
* My LinkedIn activity spiked between May and July, during my virtual internship when I shared four complete data analysis projects with detailed reports.
* Finally, using Power BI, I’ve transformed my LinkedIn analytics into a powerful, easy-to-use dashboard.
  
## Key takeaways:
Now that I know which types of posts are most engaging, I can create more valuable content, using visuals and project work to experiment with data analysis tools and explain them through simple posts and articles.

From this insightful analysis, I can now make informed decisions based on the knowledge of:

- What types of posts get the most engagement?
- How can I improve low-performing posts and create more engaging content?
- How often and when should I post to maximize engagement?

## 7. LinkedIn Analytics Dashboard:

I can now add my weekly LinkedIn analytics data and refresh this dashboard to get regular updates on my posts’ performance and engagement metrics.
![Dashboard](https://github.com/user-attachments/assets/26e31264-49b9-4594-ae6b-6dfd59710197)

## Appendix:

* [LinkedIn Analytics: Telling my LinkedIn Story with Power BI - Article](https://www.linkedin.com/pulse/linkedin-analytics-arpita-deb-uhiuc/?trackingId=rlNLsqG4TDeIC5I5m%2Be42A%3D%3D)
