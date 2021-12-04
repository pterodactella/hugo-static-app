---
layout: post
title: "Kaggle dataset: The Office (US) - Complete Dialogues?Transcript"
date: 2021-12-03T18:26:38+01:00
description: ""
featured_image: "/images/group.jpg"
draft: false
---
We further expand the datased by including the Complete Dialogue/Transcript. After formatting the data, once can look at how many lines the main characters have and how this varies from season to season. 

![image description](/images/lines.png)

Michael, the main character and Regional Manager of the Scranton branch is the character with the most lines, which can also be seen from the graph above, even though he left the show in season 7 and did not participate in the last two seasons. Now, we will dive into the line count by season for each of the main characters, and see who became the main character after Michael has left The Office.

![image description](/images/lines2.png)

For the first 7 seasons, Michael stayed the main character. The second place is shared by Dwight and Jim through the first 8 seasons. In season 8, Andy gets promoted to regional manager, to replace Michael, and hence, he is the character with most lines during season 8. However, in season 9, it is Dwight who gets promoted to regional manager, thus being the dominant character of the season. Consequently, a correlation can be seen between who is the regional manager od the Scranton brach and the character with most lines.

This is related to the analysis done with the IMDB ratings. Season8, after Michael left, is rated as the worst season. This can also be influenced by the fact that Michael's replacement was Andy, who is known not to be liked by the audience. After season 8, Andy was replaced in the role of regional manager by Dwigth, and the ratings went up slightly. Can it be that the writers noticed that Andy was not liked by the audience? 


### Top speaker influence on the episode rating

It was seen that on average, Michael is the top speaker for the first 7 seasons. However, it is time to investigate whether a relation between the top speaker in every episode of every season and the IMDb rating exists.


![image description](/images/boxplot3.png)

For all episodes in the show, 7 main speakers were identified. 

As we previously suspected, when Michael is the top speaker in an episode, that episode tends to obtain higher ratings. 

However, when Andy speaks, the episode ratings are lower. Hence, this explains the low ratings of season 7. However, in season 8, Andy was replaced as Regional Manager by Dwigth, who also tends to obtain low raitings, an average of 7.8 in comparison to 7.7 from Andy. Hence, this also explains why the ratings of season 9 were low. 

A smarter choice would have been to replace Andry with Jim, which has almost the same success rate when it comes to high episode ratings as Michael.

### Top speaker influence on the episode Viewership 
Let's repeat the previous analysis, but this time let's analyse the influence of the top speaker in episode views.

![image description](/images/boxplot4.png)

Once again, Michael and Jim have a positive influence in the views when they are the top speakers of the episodes. However, when Pam is the top speaker, the views are the lowest. This might be because generally she does not make many jokes and she is more calm, so people could see her as boring. 

On the other hand, Dwight has a very specific sense of humor. He is very sarcastic, thus viewers might understand and/or like it. 


### How many times the characters say their favorite lines?

#### That's what shes said

![Alt Text](/images/michael.gif)
First, let's look into the number of 'That's what she said jokes' made throughout all 9 seasons.

![image description](/images/joke1.png)

The number of "That's what she said" jokes starts in season 2 and grows until season 4 after which the joke is not said as often. In season 7 when Michael leaves, no one says it. Then, in season 9, it is said again Once by Michael and once by Creed. The person who says the joke the most is Michael, who repeated the joke 23 times.

#### Dunder Mifflin, this is Pam
As the receptionist, for the first 4 seaons, whenever Pam was answering the phone, she was said: 'Dunder Mifflin, this is Pam'. Let's look into how many times she actually said it:
![Alt Text](/images/pam.gif)

The number of times Pam said the joke is 18.

#### Number of times Angela talks about her Cats

![Alt Text](/images/angela.gif)

The number of times Angela talks about her cats is 37.


#### Number of times Andy calls Jim Tuna

![Alt Text](/images/andy_tuna.gif)

The number of times Andy calls Jim Tuna is 54.


#### Number of times Kelly calls or talks about Ryan

![Alt Text](/images/kelly.gif)

Kelly calls or talks about Ryan 12 times.


#### Number of Times Dwight says Assistant Regional Manager 

![Alt Text](/images/dwight.gif)

Dwight says Assistant Regional Manager is 20 times.


### Sentiment Analysis
Througout the show each character is exposed to a multitude of feelings, some are in pain and some of them are full of excitement. 
However, from season to season their perception of awareness is changing and one can not be sure which character is the most positive
and who does not share the same enjoyment. To see the variation on the character sentiments, we take a closer look at the transcripts
for each character, we can observe which character is the happiest and who has the lowest sentiment score during each season. 
The diagram below represents the sentiment score for every main employee from Dunder Mifflin. The first two seasons Meredith, Michael and Jim 
are rather positive, everyone being happy with the way things are. Michael being the regional manager, Jim constantly pranking Dwight and looking 
forward to a relationship with Pam and Meredith not having yet an alcohol problem. Starting with Dwight the characters tend to be more neutral and 
at the bottom of the list there is Darryl that is constantly annoyed by Michael, Angela that only cares about her cats and Stanely being the office grump.
Kelly is in a constant change of mood and when in season two Ryan appears she tends to be more happy.
Season three, four and five keeps Stanley's at the bottom of the list because he does not like to find himself in constant meetings and only loves Pretzel Days.
Moreover, we can observe Michael being constantly in top three, meaning that whenever there is a problematic situation in the office he always likes to 
take things positively and develops a multitude of characters to break the created tension in the office. From being neutral Dwight drops a few positions back
due to the fact of taking things too serious and being prancked by Jim.
Season five and six gives Toby a higher sentiment score due to the fact that he is about to leave for Costa Rica and also was invited to participate in the
Scranton Strangler court case as a jury. Because Dunder Mifflin was sold to another company, new characters start to appear like Gabe, Erin, Pete and Clark
that have a rather positive score due to the fact that they met their new colleagues and tend to get along with everyone. At the bottom of the list Meredith,
Stanley, Darryl and Angela are not pleased with the new changes. 
Season seven is when Michael leaves Dunder Mifflin, this being the main reason why he did not make it into top 5. On the other hand Karen has the biggest
happiness score due to the fact of being pregnant. New characters are introduced such as Robert California, whit a big sentiment score because of his role as
a CEO of Dunder Mifflin. At the bottom of the list there are the usual names always grumpy and self centered(Angela) and Nelie who has filmed in only one series
of that season but still making a bad impression from the begining. 
After Michael leaves Andy is appointed manager and his dream to be promoted is fulfilled, thus, receiving a high sentiment score. Nellie from being last made it into top 
ten due to the fact of being promoted to a higher position and at the characters with the lowest sentiment score being the usual grumpy faces of Angela, 
Stanley, Toby and Meredith. 
Season nine has somewhat two biast sentiment scores because both Roy and Michael appear only in one of the series, and in the middle there is Dwight. One can
say that was the most Dwight has achieved during the sitcom, thus, he and Angela have a higher sentiment score than before.



#### Characters based on sentiment score:

![image info](/images/graph.png)


 


### LabMT method
 
The diagram below represents 10 happiest and saddest characters out of the main one's according to LabMT method. We can definetely state that Michael is the most positive
of them all, being the regional manager that can not affors to have a sad influence on the office. The diagram is quite accurate because Toby is the
saddest character, being constantly bullied by Michael for his lack of adventure and monotonous lifestyle. Jim and Pam are in the top 10 happiest characters
because of their relationship development throughtout the seasons, but did not make the top 5 as like in any other relation sad moments are there as well.


#### Characters based on sentiment score:

![image info](/images/sentiment_score.png)



### Vader method

According to the Vader method for calculating sentiment analysis based on each character transcript, Roy has the biggest sentiment score. Why would not he,
his only moment of sadness being his breack-up with Pam. After that he became a successful businessman living the dream and making everyone else envy him.
However his score is biast. due to the fact that he did not appear after the season five and appeared only once in season nine as a successful character, 
receiving an overall sentiment score higher than anyone.
Michael in the second place stays as the most consistent character according to both methods. Being the regional manager Michael had to stay positive 
in order not to bring sad thoughts into the office that will demotivate everyone else. Jim and Pam have always been good to everyone from the office, besides that
Pam was a receptionist and afterthat became the office administrator, meaning that she needed to stay positive while interacting with everyone.
Starting with dwight that has a reathe sarcastic sense of humour which is often interpreted as negative, characters like Toby, Stanley, Angela
and Jan tend to have a lower sentiment score due to the fact that they are mean to everyone else that does not like their lifestyle. Stanley and Jan were always mean to 
Michael because of his nature and lack of responsibility which denotes clearly their low score of happiness. Toby being the HR employee was always neutral
suffering from his divorce while Meredith treated her sadness with alcohol. 


#### Characters based on sentiment score:

![image info](/images/sentiment_score1.png)




### Wordclouds based on transcripts

Below figure is a representation of the most used words by the 25 main characters from the TV show throughout 9 seasons. 
Looking at the wordclouds not much can be said about every character, most of the characters use the words: hey, know, right, oh and yeah.It makes sense, since
they are working in the same environment and tend to have conversations betwenn each other. Whenever they approach someone they say HEY or linking words like,
oh, uh, okay. However, for some of the characters the wordcloud are quite accurate: From Angela's we can see that she mostly used Dwight and senator, whom she used to date
and Kevin that sits next to her in the office. Oscar's wordloud most used word is Angela because they both work in the same department, Jan used to be the 
secretary of the CEO which is David Wallace, Gabe used to date Erin this is why Erin is the most used word by him and Phyllis sat near Andy who after that became the manager.
Another accurate wordloud is for Pam, due to the fact that she used to be a secretary and used a lot of bigrams and trigrams and the most accurate of them all is
Stanley's wordcloud. From there we can see that he loved pies and needed to work becuase of the money and afterthat at the retirement he went to Florida.   


#### Characters based on sentiment score:

![image info](/images/word_cloud.png)
