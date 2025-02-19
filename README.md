# Social-Buzz

## Project Background

Social Buzz was founded by two former engineers from a large social media conglomerate, one from London and the other from San Francisco. They left in 2008 and both met in San Francisco to start their business. They started Social Buzz because they saw an opportunity to build on the foundation that their previous company started by creating a new platform where content took center stage. Social Buzz emphasizes content by keeping all users anonymous, only tracking user reactions on every piece of content. There are over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments. This ensures that trending content, as opposed to individual users, is at the forefront of user feeds.

Over the past 5 years, Social Buzz has reached over 500 million active users each month. They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively.
Due to their rapid growth and digital nature of their core product, the amount of data that they create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain. Out of the 250 people working at Social Buzz, 200 of them are technical staff working on maintaining this highly complex technology.

### Business Problem:

Up until this point, they have not relied on any third party firms to help them get to where they are. However there are 3 main reasons why they are now looking at bringing in external expertise:

1) They are looking to complete an IPO by the end of next year and need guidance to ensure that this goes smoothly.

2) They are still a small company and do not have the resources to manage the scale that they are currently at. They could hire more people, but they want an experienced practice to help instead.

3) They want to learn data best practices from a large corporation. Due to the nature of their business, they have a massive amount of data so they are keen on
understanding how the world's biggest companies manage the challenges of big data.

## Data Structure and Initial checks

**User ID**: Unique ID of the user (automatically generated) Name: Full name of user Email: Email address of user

**Profile User ID**: Unique ID of a user that exists in the User table Interests: Interests of the associated user Age: Age of the associated user

**Location User ID**: Unique ID of a user that exists in the User table Address: Full address of the user

**Session User ID**:  Unique ID of a user that exists in the User table Device: Mobile device that they used for this session on the application Duration: Amount of time in minutes that this user stayed active on the application during this session

**Content ID**: Unique ID of the content that was uploaded (automatically generated) User ID: Unique ID of a user that exists in the User table Type: A string detailing the type of content that was uploaded Category: A string detailing the category that this content is relevant to URL: Link to the location where this content is stored

**Reaction Content ID**: Unique ID of a piece of content that was uploaded User ID: Unique ID of a user that exists in the User table who reacted to this piece of content Type: A string detailing the type of reaction this user gave Datetime: The date and time of this reaction

**ReactionTypes Type**: A string detailing the type of reaction this user gave Sentiment: A string detailing whether this type of reaction is considered as positive, negative or neutral Score: This is a number calculated by Social Buzz that quantifies how “popular” each reaction is. A reaction type with a higher score should be considered as a more popular reaction.


![Screenshot 2025-02-19 162753](https://github.com/user-attachments/assets/cea638af-a61c-4d53-98be-09927730ec34)







