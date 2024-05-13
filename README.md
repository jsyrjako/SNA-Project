# SNA-Project


# Group information

| Name             | Student ID | Email                      |
| ---------------- | ---------- | -------------------------- |
| Janne Yrjänäinen | Y58554010  | jyrjanai20@student.oulu.fi |
| Joona Syrjäkoski | Y58172266  | jsyrjako20@student.oulu.fi |

## Project Description
Twitter Friendship Network Analysis

The project aims to analyze the Twitter friendship network.




## Data Description
### Twitter Friends and hashtags

The large scale Twitter friendship dataset available at [Twitter Friends (kaggle.com)](https://www.kaggle.com/datasets/hwassner/TwitterFriends/data). The data is in the form of a CSV file. 

This datasets is an extract of a wider database aimed at collecting Twitter user's friends (other accound one follows). The global goal is to study user's interest thru who they follow and connection to the hashtag they've used.

The data contains the following columns:
- avatar: URL to the profile picture
- followerCount: the number of followers of this user
- friendsCount: the number of people following this user
- friendName: stores the @name (without the '@') of the user (beware this name can be changed by the user)
- id: user ID, this number can not change (you can retrieve screen name with this service: https://tweeterid.com/)
- friends: the list of IDs the user follows (data stored is IDs of users followed by this user)
- lang: the language declared by the user (in this dataset there is only "en" (english))
- lastSeen: the time stamp of the date when this user have post his last tweet
- tags: the hashtags (with or without #) used by the user. It's the "trending topic" the user tweeted about
- tweetID: ID of the last tweet posted by this user

#### Acknowledgements
This data set is build by Hubert Wassner (me) using the Twitter public API. More data can be obtained on request (hubert.wassner AT gmail.com), at this time I've collected over 5 milions in different languages. Some more information can be found here (in french only) : http://wassner.blogspot.fr/2016/06/recuperer-des-profils-twitter-par.html