# Project 3: Reddit Web API & Classification



## Problem Statement

The Biden presidential election campaign team is trying to capture more voter share, specifically in the digital space where republician presidential candidate Donald Trump holds a stronger and more effective presence. By developing a text classifier to analyze online postings, using reddit as a base reference, the campaign team hopes to gain more insights into understanding sentiment in both the democratic and republican camps. 2 models: Logistic Regression and Naive Bayes, will be evaluated. This will allow the team to optimise resources and online efforts for the most impactful outreach and also use it to analyze other media platforms. Success will be measured by having a high degree of classification accuracy above the baseline score.


## Executive Summary

The Biden Presidential Election Campaign Team is poised to help strategise, coordinate and execute the Biden's campaign efforts in the 2020 Presidential Race. Part of the key initiatives taken on within the team's strategic plan would be to use data driven methods such as web classification models to identify opportunities and weaknesses for structuring the campaigns.

Currently, the presidential race is down to very narrow margins. The republican representative Donald Trump has a stronger and more effective online presence due to his engagement on social media platforms. This presents serious concern in a tight race given the volatility of voter sentiment. Due to the electorates being more online savvy in this generation, the campaign team would like to secure more support by gaining insight of online sentiment and to appeal to potential voters through these findings.

To achieve this, the Biden campaign team is hoping to leverage on web api data extraction and natural language classifier techniques on various web discussion platforms. To construct a base reference, data pulled from subreddits under the democrat and republican categories will be used as a basis to train and select the best classifier model. With the use of the classifier, the team are better able to monitor trending topics that voters are concerned about most and gauge online sentiment for opportunities. This would enable Biden to be better prepared in communicating the most effective message on his trail.
Being staffed with experienced data analysts that have served in previous election campaign, the Biden campaign election team is seeking to gather more precise information on the US voter base. With this information, the firm hopes to optimize strategy and resources from information gathered using the developed model.


## Data Dictionary

<font color=black><b>Reddit Data Dictionary (after cleaning)</b></font>
    
|Feature                        |Type    |Dataset|Description
|:-----------------------       |:---    |:---|:---
|<b>subreddit</b>                |string|project_data|Subreddit category
|<b>title</b>                     |string |project_data|Post title text content



## Conclusion & Recommendations


<font color=black>
    
The genesis of this project was to compete strongly with Trump in popularity presidential polls by finding and developing a classification model that could accurately identify web posts as belonging to democratic or republican voters. This would gain insight as to the trending issues among both camps and help the Biden campaign team forge a solid strategy to win over more supporters.
   
To recap, the following methodology was performed to meet these objectives:
<ul>
<li>Information was scraped from 2 relevant subreddits belonging to Democratic and Republican board as a starting basis</li>
<li>The individual subreddit data was first analyzed for the word trends during EDA</li>
<li>The merged data was also analyzed for the word trends during EDA</li>
<li>The training and test splits were created</li>
<li>Subsequently, four combination of vector-classification models were run to derive the best performing model</li>
<li>Gridsearch hyperparameters tuning and stopwords were used to refine the model</li>
<li>Parameters and word coefficients of the selected classification model were also derived</li>
 </ul>   
The best classification model identified for the campaign team turned out to be the Logistic Regression using the Count Vectorizer. The use of this tool could achieve training accuracy rates of up to 68%.
    
Also identified, were important top performing key words that were common to both the democrats and republicans through the barplot and wordcloud visualizations. To name the most relevant ones were words pertaining to the Black-Lives-Movement (BLM), the ongoing racial protests, the involvement of the police in the riots, the coronavirus and also both the presidential candidates.
    
Using the these results, the following <b>inferences</b> can be made:
<ul>   
<li>Unity with the black community will be an important card to play given that the race gap is narrow and that Biden has the possible chance to reinforce and win over more black support</li>
<li>Trump is a very prominent and controversial talking point amongst both camps and hence a strategy catered towards him might sway public opinion</li>   
<li>Although the pandemic situation has been temporarily overshadowed by the Minnneapolis riots, it still remains a concern amongst the electorate</li> 
<li>Recency of events is a very critical component of how the model functions and is also very relevant to the presidential race given it reacts to ever changing events daily</li> 
</ul>   
To this end, the campaign committee makes the following <b>recommendations</b>:
<ul>
<li>Communicate a message of solidarity with the black community</li>  
<li>Get endorsement from prominent black figures such as Obama</li>      
<li>Gain publicity by engaging in black community events such as talk shows</li>     
<li>Consider having a colored running mate VP for black representation</li>      
<li>Spread online campaign on black unity using online and printed media</li>    
<li>Come up with a comprehensive plan to combat the Covid 19 situation</li>    
<li>Communicate the plan strongly and emphasize on the rising infection numbers and death toll</li> 
</ul>   
Actioning a response based on the above recommendations would help Biden win more support in dealing with two big national crises and show confidence in dealing with the hard challenges faced by the nation. This would in turn help to swing more undecided voters or even republican supporters through a rational approach on tackling issues close to them.

Future steps to move this project forward would be to gather even more data to formulate the model basis such as collecting comments from reddit, extracting a greater range of data beyond the 1,000 post limit or to start executing the model on additional online discussion platforms such as social media.

</font>