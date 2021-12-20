# Final Project Write up

 - Ziyuan Cai
 - Sisun Cheng
 
 ## 1. Introduction
 
 ## 2. Data
 
 ## 3. Methods
 
To analyze people’s comment on National Parks, we got Twitter text with topics of each National Park’s name from Twitter API. We used the name of every national parks as the search word to get the twitter of maximum 1000 and then do the sentiment analysis with all the biased tweets of each national parks, calculating polarity using the textblob package. Combined the polarity results and the normalized visitors from 2007-2016 in 50 and 50, we figured out the score of each national parks, which decides the ranking result.

For information part, we found the states and counties that every national parks intersect with and dragging out the census data using cenpy package and census API. Same as census, we used the osmnx package to count the parking feilds and restaurants in certian parks' areas.

 ## 4. Results
 
Only a few of national parks don't contain enough tweets, which can be explained as they contain little discussion through public, and as a result, they are not popular at all. The top 10 national parks are listed in order as follows: Great Smoky Mountains National Park, Saguaro National Park, Petrified Forest National Park, Crater Lake National Park, Redwood National Park, Katmai National Park, Mesa Verde National Park, Grand Canyon National Park, Everglades National Park, Channel Islands National Park. Because twitter analysis is instant, so polarity analysis has certain volatility. In addition, we want to provide travel guidance during the Christmas period, so we chose to conduct twitter analysis in December. From the result, some really famous national parks is not in the list of top 10, maybe because they are not suitable to visit in winter, which can be indicated from the tweets post by the public.

There are national parks all over the United States, so their related attributes will be very different. Katmai National Park has the largest crime numbers nearby, Saguaro National Park has the most number of parkings around and Everglades National Park has the most surrounding restaurants. There is no significant difference in median house income attributes, because the area closest to the national parks must contain a small population, and only the urban areas in the nearby county will have a relatively high income. 


 ## 5. Conclusions
