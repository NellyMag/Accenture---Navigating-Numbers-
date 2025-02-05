<h2>Project Background</h2>

Social-Buzz, a rapidly expanding media content creation company that prioritizes user anonymity and monitors user reactions on every piece of content. 

The company is currently facing challenges related to managing its expanding scale. Over 100,000 pieces of content, including text, images, videos, and GIFs, are posted daily. Accenture has begun a 3-month project to address key areas, including an audit of Social Buzz’s big data practice, recommendations for a successful IPO, and an analysis to identify the company’s top 5 most popular content categories. Given the substantial amount of data available, Social Buzz needs an effective strategy to leverage this information and maximize its potential for growth.

This project thoroughly analyzes their content categories and highlights the top 5 categories with the largest aggregate popularity.




Insights and recommendations are provided in the following key areas:

+ Content categories analysis: An analysis of the content and reactions.


Excel steps taken to clean and model the data can be found [here](https://drive.google.com/file/d/1AbKj5FTOz8UP8oWLwmpT2g3_Ay_5GNX1/view?usp=sharing).

----

<h2>Data Structure</h2> 

Data source: these datasets were provided by Accenture and stored on [forage](https://www.theforage.com/dashboard). Forage is a free virtual work experience program from top companies.

The dataset consists of a sample of over 25,000 reactions, 16 distinct qualitative content, and a quantitative score that is directly related to the sentiment and type of the reaction types.

<img width="503" alt="Image" src="https://github.com/user-attachments/assets/8a0bac18-4e46-4818-8b31-6d19d438da67" />

**Content**<br/>
ID: Unique ID of the content that was uploaded (automatically generated) <br/>
User ID: Unique ID of a user that exists in the User table<br/>
Type: A string detailing the type of content that was uploaded<br/>
Category: A string detailing the category that this content is relevant to<br/>
URL: Link to the location where this content is stored

**Reaction**
Content ID: Unique ID of a piece of content that was uploaded<br/>
User ID: Unique ID of a user that exists in the User table who reacted to this piece of content<br/>
Type: A string detailing the type of reaction this user gave<br/>
Datetime: The date and time of this reaction

**ReactionTypes**<br/>
Type: A string detailing the type of reaction this user gave<br/>
Sentiment: A string detailing whether this type of reaction is considered as positive, negative, or neutral<br/>
Score: This is a number calculated by Social Buzz that quantifies how “popular” each reaction is. A reaction type with a higher score should be considered a more popular reaction


**Steps taken to clean the data**

**Data Cleaning**

Removed rows that have values that are missing
Changed the data type of some values within a column
Removed columns that are not relevant to this task.

The detailed steps can be found [here](https://drive.google.com/file/d/1AbKj5FTOz8UP8oWLwmpT2g3_Ay_5GNX1/view?usp=sharing).

---
<h2>Summary</h2> 

The analysis of Social Buzz’s content performance reveals that Animals (31.60%) and Science (17.64%) are the top two categories driving the highest engagement, suggesting a strong interest in educational and lifestyle content. Healthy Eating (17.19%), Technology (17.04), and Food (16.53%) also rank highly, but with slightly less consistent engagement. The overall trend shows stable content activity year-round, with peaks in January and May and a slight dip in February. Furthermore, users express more sentiment reactions to videos contents. These findings highlight key areas for growth and provide actionable insights for refining the company’s content strategy moving forward.

<img width="802" alt="Image" src="https://github.com/user-attachments/assets/0f198f8c-7026-4fe9-8ba7-2bf0d8f641bc" />
<br />




**Monthly Performance**


<img width="466" alt="Image" src="https://github.com/user-attachments/assets/a56ac5b5-bdd5-428d-be5f-ed848e3e227a" />


+ **Peak Activity**: January and May saw the highest levels of activity.

+ **Dip in February**: There was a noticeable decrease in activity during February.

+ **Stable Months**: Engagement remained consistent around the same level for most months, from June to December.

+ **General Trend**: A slight decline in early year, with steady engagement throughout the rest of the year.


**Conclusion**

**Recap of Findings**:
Animals and Science are the top two performers, and the engagement suggests a growing interest in both educational and lifestyle content.

**Actionable Insights**:
Focus content strategy on categories like Animals and Science, as they have the highest popularity.
Consider further engagement strategies for other categories like Technology and Healthy Eating.<br/>
+ Example: post 30 second videos about healthy eating or technology related topics.<br/>

Conduct another content analysis at a later phase to check on the success of this plan.



