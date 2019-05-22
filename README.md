# Web Mining Final Project

## Jacob McCullough
## Due: April 23, 2019
## Topic: Whats going on in the NFL(National Football League)
In my project I analyzed every team from every conference & division in the NFL. By Conferance & Division these teams are:
## American Football Conference(AFC) <img src="https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/American_Football_Conference_logo.svg.png" width="60" height="60">

### East Division
##### New England Patriots - 4,446,030 Twitter Followers
##### Miami Dolphins - 989,340 Twitter Followers
##### Buffalo Bills - 981,916 Twitter Followers
##### New York Jets - 1,222,479 Twitter Followers
#### Division Total: 7,639,765 Twitter Followers
### North Divison
##### Baltimore Ravens - 1,456,224 Twitter Followers
##### Pittsburgh Steelers - 3,423,502 Twitter Followers
##### Cleveland Browns - 1,198,285 Twitter Followers
##### Cincinnati Bengals - 827,867 Twitter Followers
#### Division Total: 6,905,881 Twitter Followers
### South Division 
##### Houston Texans - 1,859,151 Twitter Followers
##### Indianapolis Colts - 1,029,521 Twitter Followers
##### Tennessee Titans - 755,070 Twitter Followers
##### Jacksonville Jaguars - 659,909 Twitter Followers
#### Division Total: 4,303,651 Twitter Followers
### West Division
##### Kansas City Chiefs - 1,277,876 Twitter Followers
##### Oakland Raiders - 1,602,736 Twitter Followers
##### Los Angeles Chargers - 839,844 Twitter Followers
##### Denver Broncos - 2,639,205 Twitter Followers
#### Division Total: 6,359,661 Twitter Followers

## National Football Conference(NFC) <img src="https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/National_Football_Conference_logo.svg.png" width="60" height="60">
### East Division
##### Dallas Cowboys - 3,795,103 Twitter Followers
##### Philadelphia Eagles - 3,424,277 Twitter Followers
##### Wahington Redskins - 1,247,331 Twitter Followers
##### New York Giants - 1,815,939 Twitter Followers
#### Division Total: 10,282,650 Twitter Followers
### North Division
##### Chicago Bears - 1,754,554 Twitter Followers
##### Minnesota Vikings - 1,282,729 Twitter Followers
##### Green Bay Packers - 2,219,726 Twitter Followers
##### Detroit Lions - 1,344,276 Twitter Followers
#### Division Total: 6,601,285 Twitter Followers
### South Division 
##### New Orleans Saints - 1,390,527 Twitter Followers
##### Atlanta Falcons - 2,343,996 Twitter Followers
##### Carolina Panthers - 3,014,170 Twitter Followers
##### Tampa Bay Buccaneers - 768,203 Twitter Followers
#### Division Total: 7,516,896 Twitter Followers
### West Division
##### Los Angeles Rams - 843,035 Twitter Followers
##### Seattle Seahawks - 2,355,021 Twitter Followers
##### San Francisco 49ers - 2,062,316 Twitter Followers
##### Arizona Cardinals - 916,934 Twitter Followers
#### Division Total: 6,177,306 Twitter Followers <br/><br/>
## Goals
(1) I would like to discover how popular each team is compared to the others.<br/>
(2) Predict what time of the year it is, (example: pre-season, regular season, postseason,<br/>
& off-season).<br/> (3) I would like to then try and estimate how succesful a team was this passed season,<br/>
or how optimistic they are about the upcoming season.<br/><br/>
## Questions
(1) Can we determine popularity based on twitter analysis<br/>
(2)Can we determine what time of the year it is based off of twitter analysis (off-season, preseason, regular season, post-season)<br/>
(3)Can we determine how well a team is doing/expected to do based off of twitter analysis<br/><br/>
## How To Do This
(1) To do this project I need to access the offical twitter accounts of all 32 teams in the NFL.<br/>
(2)I would then pickle each teams last 100 tweets.<br/> (3) I would then run all tests and analysis<br/> 
on them collectings data, forming opinons, and coming to conclusions along the way.<br/><br/>
## Modules Used
pickle</br>
datetime</br>
collections</br>
Counter</br>
mathplotlib.pyplot</br>
SentimentIntensityAnalyzer</br>
nltk</br>
tweepy</br><br/>
## Answers
(1) We can view a teams profile and can determine popularity loosely based off of twitter followers/success(Super Bowls)</br>
(2) We can determine what time of year it is based off of a word analysis, to look for key words. Example(free, agent, draft, signing)<br/>
so we can conclude that it’s the off-season</br>
(3) We can look at key words as well as do a sentiment analysis to determine the expectations/current success of  a team</br></br>
## Results & Thoughts
From the data that we collected we were able to answer all of our questions that we asked, and show the results to prove it.</br></br>
#### Graph of Highest and Lowest # of Twitter Followers

![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Highest%26Lowest_Followers.PNG)<br/><br/>
### Sentiment Analysis Graphs
#### AFC East
##### (Top Left)New England Patriots, (Top Right)Miami Dolphins, (Bottom Left)Buffalo Bills, (Bottom Right)New York Jets<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Patriots_Sentimet_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Dolphins_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Bills_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Jets_Sentiment_Analysis.PNG)
#### AFC North
##### (Top Left)Baltimore Ravens, (Top Right)Pittsburgh Steelers, (Bottom Left)Cleavelend Browns, (Bottom Right)Cincinnati Bengals<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Ravens_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Steelers_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Browns_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Bengals_Sentiment_Analysis.PNG)
#### AFC South
##### (Top Left)Houston Texans, (Top Right)Indianapolis Colts, (Bottom Left)Tennessee Titans, (Bottom Right)Jacksonville Jaguars<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Texans_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Colts_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Titans_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Jaguars_Sentiment_Analysis.PNG)
#### AFC West
##### (Top Left)Kansas City Chiefs, (Top Right)Oakland Raiders, (Bottom Left)Los Angeles Chargers, (Bottom Right)Denver Broncos<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Chiefs_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Raiders_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Chargers_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Broncos_Sentiment_Analysis.PNG)
#### NFC East
##### (Top Left)Dallas Cowboys, (Top Right)Philidelphia Eagles, (Bottom Left)Washington Redskins, (Bottom Right)New York Giants<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Cowboys_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Eagles_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Redskins_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Giants_Sentiment_Analysis.PNG)
#### NFC North
##### (Top Left)Chicago Bears, (Top Right)Minnesota Vikings, (Bottom Left)Green Bay Packers, (Bottom Right)Detroit Lions<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Bears_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Vikings_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Packers_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Lions_Sentiment_Analysis.PNG)
#### NFC South
##### (Top Left)New Orleans Saints, (Top Right)Atlanta Falcons, (Bottom Left)Carolina Panthers, (Bottom Right)Tampa Bay Buccaneers<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Saints_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Falcons_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Panthers_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Buccaneers_Sentiment_Analysis.PNG)
#### NFC West
##### (Top Left)Los Angeles Rams, (Top Right)Seattle Seahawks, (Bottom Left)San Francisco 49ers, (Bottom Right)Arizona Cardinals<br/>
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Rams_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Seahawks_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/49ers_Sentiment_Analysis.PNG)
![image description](https://github.com/44520-w19/wm-project-final-razorwired1124/blob/master/Presintation%20Material/Cardinals_Sentiment_Analysis.PNG)
## Conclusion
In conclusion, from the data that we collected we were able to answer all of our questions that we asked, and show the results to prove it. 

(1)Can we determine popularity of teams(YES)<br/>
   *Most Super Bowls & Followers = Patriots<br/>
   *Least Super Bowls & Followers = Jaguars<br/>

(2)Can we determine the time of year(YES)<br/>
   *We are currently in the off-season<br/>

(3)Can we determine how well a team is doing/expected to do(YES)<br/>
   *Most teams are neutral to positive which we<br/>
    &nbsp; can assume means they are hopeful/optimistic<br/>
