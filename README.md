# IMDB

IMDb, the world's most popular and authoritative source for movie, TV and celebrity content.

![图片](https://user-images.githubusercontent.com/11934986/114636035-ae98bd00-9cf8-11eb-813a-0f50b8a57ebb.png)


Project 2: Market-basket analysis

Some actors often appear in movies together, maybe they are good partners, or maybe they are in some other relationships. The purpose of this article is to find actors who often appear in movies at the same time, analyzing the IMDb dataset in which movies as baskets and actors as items. IMDb is an online dataset of information concerning movies, videos, TV programs, etc. To perform a market-basket analysis, that is to find frequent item sets, the A-prior algorithm is applied to reduce the number of pairs that must be counted. To make sure the system can scale up with larger dataset, SON algorithm is implemented in Spark to achieve it.![image](https://user-images.githubusercontent.com/51139288/120875124-78feaa80-c5aa-11eb-94c2-62b849a6f995.png)



The «IMDB» dataset is published on Kaggle, under IMDb non-commercial licensing. The analysis is done considering movies as baskets and actors as items.
