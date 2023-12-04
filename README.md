# SocialMediaVisualizations

## Section 1 - Project Description
### Questions
1) What is the distribution of user ratings and reviews for different Android app categories?
   - This question will help us understand the user sentiment towards different types of Android apps. It will also reveal which categories tend to receive higher ratings and more reviews, indicating higher user engagement. Understanding the distribution of user ratings and reviews across app categories is crucial for developers and marketers. Positive reviews and high ratings significantly impact app visibility and trust among potential users. Research has shown that higher ratings lead to increased downloads and user retention.
   - [Source](https://www.alchemer.com/resources/blog/differences-between-ios-and-android-app-ratings-and-reviews/)
   
2) Is there a correlation between app/category and score rating?
   - Analyzing user engagement metrics across different app categories will highlight the areas where users are most active and interested. This information is crucial for developers and marketers to focus their efforts on high-engagement categories. Identifying app categories with the highest user engagement provides valuable insights for developers and marketers looking to target specific demographics or optimize their app offerings. It allows for more targeted marketing efforts and can lead to increased user acquisition and retention.
   - [Source](https://www.businessofapps.com/insights/ratings-reviews-affect-consumer-decision-download-apps/)

3) Is there any correlation between the various ratings and the device being an Android or iOS product?
   - This question will help us determine if higher ratings are associated with the device being an Android or an Apple product. It can provide insights into the relationship between device popularity and user satisfaction. Investigating this correlation is essential for developers. It helps them determine if increasing ratings directly translates to higher user satisfaction between product types.
   - [Source](https://www.businessofapps.com/data/most-popular-apps/)


## Section 2 - Data Description and Upload
### Sources
1) Kaggle: 🤖Android vs iOS🍎 Device Benchmarks📊
   -[Source](https://www.kaggle.com/datasets/alanjo/android-vs-ios-devices-crossplatform-benchmarks/)
   - We were able to find a CSV file dataset on Kaggle that breaks down Android versus iOS device benchmarks into different columns including CPU, GPU, Memory, User Experience and total ratings.
3) Kaggle: Top 20 Play Store App Reviews (Daily Update)
   -[Source](https://www.kaggle.com/datasets/odins0n/top-20-play-store-app-reviews-daily-update?rvi=1)
   - The second data set is a CSV file containing app reviews of the top twenty Google Play apps. The columns of this data include: app name, the content of the review, the review ID, and the score for each review. We used the groups function in Tableau in order to group the apps by the category they fit into.

These are the sources from the Kaggle website that we used for our analysis. To access them, click the link and it will take you to the Kaggle websiite. From there, hit the download button and upload these data sets into Tableau in order to create visualizations from their data.


## Section 3 - Interpretting Visualizations
### Our Visualizations
1) Average Score Bar Chart [link to visualization](https://public.tableau.com/views/AverageScoreBarChart_17016405678550/Sheet1?:language=en-US&:display_count=n&:origin=viz_share_link)
   - This first bar chart shows the average score for each of the twenty apps. We used the app names to color the chart as well, to make it more visually appealing. 

2) Average Score by Category [link to visualization](https://public.tableau.com/views/AverageScorebyCategory/Sheet1?:language=en-US&:display_count=n&:origin=viz_share_link)
   - The second chart shows the average score by app category. We used a tree map so the size of the sections could be a nice indicator for the score that each category received.
  
3) Android vs. iOS Ratings [link to visualization](https://public.tableau.com/views/AndroidvsiOSRatings/Sheet1?:language=en-US&:display_count=n&:origin=viz_share_link)
   - This is the description for this visualization


## Section 4 - Discussion and Summary
### Article Summary


### Conversation with ChatGPT 4
We put our questions into ChatGPT 4 to see if the AI could give us more information regarding our research. Here are the responses we recieved:
1) What is the distribution of user ratings and reviews for different Android app categories?
   - As an AI, I don't have real-time access to databases or the ability to pull up-to-date statistics. However, I can tell you generally how you might go about finding this information. You would need to access a dataset that includes Android app categories, user ratings, and reviews. This data could potentially be obtained from the Google Play Store, where each app has a category, user rating, and user reviews. Once you have this data, you could use statistical analysis or data visualization tools to analyze the distribution of user ratings and reviews for different app categories. For example, you might find that games have a wider distribution of ratings than productivity apps, or that social media apps have more reviews than other categories. Please note that the distribution of user ratings and reviews can change over time and may be influenced by many factors, such as changes in app quality, user base, and market trends. Therefore, it's important to use up-to-date data and consider the context when analyzing this information.

2) Is there a correlation between app category and score rating?
   - As an AI, I don't have the ability to directly analyze data. However, I can tell you that in general, there could be a correlation between app category and score rating. For example, certain categories of apps might generally have higher ratings because they meet user needs more effectively, or because they attract a user base that is more likely to leave positive reviews. To determine if there is a correlation in your specific case, you would need to conduct a statistical analysis. This could involve calculating the correlation coefficient between app category (converted to numerical form, perhaps through one-hot encoding) and score rating, or conducting a hypothesis test to determine if the difference in average score rating between categories is statistically significant. Remember that correlation does not imply causation - even if there is a correlation between app category and score rating, it doesn't necessarily mean that the category of the app causes it to have a certain rating. There could be other factors at play.
  
3) Is there any correlation between the various ratings and the device being an Android or iOS product?
   - As an AI, I don't have real-time data or the ability to analyze specific datasets. However, I can tell you that the correlation between ratings and the device being an Android or iOS product can depend on various factors. These can include the specific app or service being rated, the user experience on each platform, the demographic of users, and more. For example, if an app is better optimized for iOS, it may receive higher ratings on Apple's App Store compared to Google Play Store, and vice versa. To determine if there's a correlation, you would need to conduct a statistical analysis on a dataset that includes ratings and device information. This could involve techniques like correlation coefficients, cross-tabulation, or regression analysis. Remember that correlation does not imply causation. Even if there's a correlation between ratings and the device being an Android or iOS product, it doesn't necessarily mean one causes the other. Other factors could be influencing the ratings.


### Conclusion:
Overall, the AI's answers were helpful in leading us in new directions for our analysis. The information we received from the Chatbot was considerably vague, since it didn't have the data sets to work with. It could only give us general answers to the questions instead of more in depth analysis about app ratings and user satisfaction. If we could put in all of the data from the Kaggle sets, then the machine could've analysed the data and given us more attuned responses. 
