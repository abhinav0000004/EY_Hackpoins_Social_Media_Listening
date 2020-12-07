# EY_Hackpoins_Social_Media_Listening
No doubt that proper analysis of human-generated data(usually on social media) can lead an organization to great success and understand their customers better. The idea behind the project was the same. We have analyzed online human-generated data about EY and other Big4 companies and analyzed them on the following aspects and divided into sections- 
* Overall **twitter performance** of EY and its comparison with other Big4 which includes what are top countries and cities with EY reach, the relation between reach and time(day wise and hourly), most frequent organization and top personalities mentioned by text, etc. 
* Analysis and comparison of various **services(Tax, Assurance, Consultancy, and Strategy & Transaction)** provided by Big4 along with analysis of maximum hashtags, mentions, likes, comments, etc.
* **Sentiment analysis** of tweets with positive and negative words and deployment of the word cloud for the same. 
* Reach of EY and its competitor from other **business news channels** or How frequently big news channel cover story related to EY and Big4. 
* **Time series analysis** of data during the COVID era(including sentiment analysis as well).
* **Geographical Analysis** for top countries like(US, UK, India, Australia, Canada, Africa) along with sentiment graphs for each.
* Frequency and Use of trending words and **technologies(like AI, ML, Data Science, etc)** used in the post texts/tweets.
* Develop **rank cards** for each Big4 on the basis of their social media performance.

We created python scripts for automation of the data scrapping and analysis process and decided to host a website to display all stats, graphs, suggestions, etc.
For future work, we are planning to completely automate the entire process and do a real-time analysis along with an in-depth analysis of other Big4 companies(same as EY) in order to get more precise and better results.

## Data Folder
### Twitter dataset is scrapped and divided into various folders which include-

1. **FamousNwesChannel** Contains the tweets of famous business news accounts that have mentioned name of company. (Separate file for each company in Big4).
2. **Happy Or Sad** contains tweets are captured based on the basic of positive and negative words in the tweet with company name. (Separate file for each company and each sentiment i.e good or bad).
3. **Services** contains tweets on the basis of various services provided by these BIG4. (Separate file for each company and each service i.e consultancy, tax, assurance and Strategy).
4. **Grofraphical** contains tweets the basis of twitter account tagged in the tweet for a particular company of a particular location. (Separate file for each company and countries).
5. **Events** Tweets containing company’s name and event(like COVID19) or technology(like Data Science,AI,Machine Learning) in it.
6. **BIG4 file** Contains all tweets with hashtag BIG4.
7. **Sample Data** contains the sample data given by hackathon committee.

## Scripts
All the scripts have been added to folder [Script_for_EY_Analysis](https://github.com/abhinav0000004/EY_Hackpoins_Team_Bolt_Social_Media_Listening/tree/main/Script_for_EY_Analysis) for all EY analysis and [Script_for_Big4_comparision](https://github.com/abhinav0000004/EY_Hackpoins_Team_Bolt_Social_Media_Listening/tree/main/Script_for_Big4_comparision) for all comparision between BIG4.

Also a [script](https://github.com/abhinav0000004/EY_Hackpoins_Team_Bolt_Social_Media_Listening/blob/main/Automated_Twitter_Data_Extracting.ipynb) has been added for scrapping twitter tweets without using twitter api.

## Sample Analysis
Words most frequently used in tweets with positive sentiment mentioning EY|  Words most frequently used in tweets with negative sentiment mentioning EY
:-------------------------:|:-------------------------:
![](https://github.com/abhinav0000004/EY_Hackpoins_Team_Bolt_Social_Media_Listening/blob/main/Sample%20OutputImages/For%20EY/HappyCloud.PNG)  |  ![](https://github.com/abhinav0000004/EY_Hackpoins_Team_Bolt_Social_Media_Listening/blob/main/Sample%20OutputImages/For%20EY/SadCloud.PNG)

While the tweet trend of Big4 is mentoning COVID19 concern :
![alt text](https://github.com/abhinav0000004/EY_Hackpoins_Team_Bolt_Social_Media_Listening/blob/main/Sample%20OutputImages/For%20Comparision/covid.png)

These are few of the analysis. More plots can be found [here](https://github.com/abhinav0000004/EY_Hackpoins_Team_Bolt_Social_Media_Listening/tree/main/Sample%20OutputImages)

## Dashboard
### Complete dashboard can be found here [Link](https://eyweb-76e3d.web.app/#/) (Open Link in incognito Mode)
