# Social-Buzz

## Client Background

Social Buzz was founded by two former engineers from a large social media conglomerate, one from London and the other from San Francisco. They left in 2008 and both met in San Francisco to start their business. They started Social Buzz because they saw an opportunity to build on the foundation that their previous company started by creating a new platform where content took center stage. Social Buzz emphasizes content by keeping all users anonymous, only tracking user reactions on every piece of content. There are over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments. This ensures that trending content, as opposed to individual users, is at the forefront of user feeds.

Over the past 5 years, Social Buzz has reached over 500 million active users each month. They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively.
Due to their rapid growth and digital nature of their core product, the amount of data that they create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain. Out of the 250 people working at Social Buzz, 200 of them are technical staff working on maintaining this highly complex technology.

### Business Problem:

Up until this point, they have not relied on any third party firms to help them get to where they are. However there are 3 main reasons why they are now looking at bringing in external expertise:

1) They are looking to complete an IPO by the end of next year and need guidance to ensure that this goes smoothly.

2) They are still a small company and do not have the resources to manage the scale that they are currently at. They could hire more people, but they want an experienced practice to help instead.

3) They want to learn data best practices from a large corporation. Due to the nature of their business, they have a massive amount of data so they are keen on
understanding how the world's biggest companies manage the challenges of big data.

To start our engagement with Social Buzz, we are running a 3 month initial project in order to prove to them that we are the best firm to work with. They are expecting the following:
- An audit of their big data practice
- Recommendations for a successful IPO
- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity

## Data Structure and Initial checks

**User ID**: Unique ID of the user (automatically generated) Name: Full name of user Email: Email address of user

**Profile User ID**: Unique ID of a user that exists in the User table Interests: Interests of the associated user Age: Age of the associated user

**Location User ID**: Unique ID of a user that exists in the User table Address: Full address of the user

**Session User ID**:  Unique ID of a user that exists in the User table Device: Mobile device that they used for this session on the application Duration: Amount of time in minutes that this user stayed active on the application during this session

**Content ID**: Unique ID of the content that was uploaded (automatically generated) User ID: Unique ID of a user that exists in the User table Type: A string detailing the type of content that was uploaded Category: A string detailing the category that this content is relevant to URL: Link to the location where this content is stored

**Reaction Content ID**: Unique ID of a piece of content that was uploaded User ID: Unique ID of a user that exists in the User table who reacted to this piece of content Type: A string detailing the type of reaction this user gave Datetime: The date and time of this reaction

**ReactionTypes Type**: A string detailing the type of reaction this user gave Sentiment: A string detailing whether this type of reaction is considered as positive, negative or neutral Score: This is a number calculated by Social Buzz that quantifies how “popular” each reaction is. A reaction type with a higher score should be considered as a more popular reaction.


<img width="932" alt="Screenshot 2025-02-19 184945" src="https://github.com/user-attachments/assets/6b74b422-38ba-40f1-9066-8f039c2d536c" />


Prior to the beginning the analyssis , a veriety of checks were conducted for quality control and familiarization with the dataset. 

### Problem Findings:

To give a background on how much data you've been creating:
- Your platform receives over 100000 posts per day which amounts to 36 500 000 posts every year, of which, this is all unstructured data making it very hard to make sense of.

In this day and age, content is king. Just look at some of the biggest platforms in the world, for example, YouTube, Facebook and Netflix... they are all content businesses... But how do we capitalize on it when there is so much? it's not just all about harvesting as much content as possible... The real value is in understanding and crunching this content to gain a deeper understanding of your audience and to therefore provide a more personalized and enjoyable experience. And this is where our data analytics expertise comes in, with the insights that we've uncovered from this task, we can show you exactly how to take analytics to production at scale.


### Process

Well, it will be approached in 5 steps:
1. #### Data understanding - the key to success on any data project is to understand the data in detail. So we took the time to understand the data model and domain of your business.
2. #### Data cleaning - after understanding your business, we then cleaned the available datasets and thought about what an ideal dataset should look like for this problem.
3. #### Data modelling - After ensuring the data was clean for analysis, we needed to process and model this data into a dataset that could precisely answer the business questions and produce the results needed.
4. #### Data analysis - With our new dataset, we used our analytical expertise to uncover insights from this dataset and to produce visualizations to describe the insights.
5. And finally we used these insights to unlock business decisions and to make recommendations on the next steps

### Insight

From our analysis, you can see that the top 5 most popular categories of posts were animals, science, healthy eating, technology and food in descending order.

<img width="447" alt="Screenshot 2025-02-19 174906" src="https://github.com/user-attachments/assets/807377fa-fb6e-48ba-8070-6f940849236d" />

Animals had an aggregate popularity score of around 74965. It is very interesting to see both food and healthy eating within the top 5, it really shows that food is a highly engaging content category. Healthy eating ranks slightly higher than food, so perhaps your user base may be skewed towards healthy eaters and health-conscious people.

Also, the data we found that there is a total of 16 unique categories of posts across your sample dataset. This includes things such as Food, Science and Animals. As well as this, there were 1897 reactions from just the animal category alone! People obviously really like animals!  and also the most common month for users to post within was January. This aligns with seasonal trends of social media users who feel the need to reconnect with people after calendar events such as Christmas. Finally, it's also interesting to see science and technology too. This may suggest that people enjoy consuming factual content and snippets of content that they can learn something from. 

But now, onto the main question... which is... what were the top 5 most popular categories of posts?

### Excutive Summary

So to summarize:
We tackled this task and found the top 5 most popular categories as asked, but also went a step further.
- found that animals and science are the two most popular categories, suggesting that users like "real-life" and "factual" content

- also found that food was a common theme amongst popular content and the most popular food category was healthy eating. 

### Recommendation

These findings could be a signal to show the types of people who are using your platform, and you could use this insight to boost engagement even further. For example, The company could run a campaign with content focused on this category or work with healthy eating brands to promote content.

Finally, as much as this analysis was insightful, we are ready to take it to the next stage and we have the expertise within us to help you realize these kinds of insights in production across your organization and in real-time. We would love to help you with this.**







