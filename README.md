# PODCAST RADAR

To answer the question 'Are podcasts in Brazil losing their hype?', I conducted a data analysis comparing the 3 biggest podcasts in Brazil (Flow, Inteligência LTDA, Podpah), analyzing views, likes, comments, and videos published over time. More explanations can be found in this video (PT-BR): https://youtu.be/REJS0ysKVtg

The .csv files contain the data I fetched from the YouTube API for the analyzed channels. I’ve made them available here in case anyone wants to work with the data and perform different analyses without needing to fetch new data from the API. Here, you’ll only find the charts with a brief explanation; the analysis was done in the YouTube video.

## Data Extraction

Through the YouTube API, I obtained the total views, subscribers, and videos produced by each channel. Shortly after, I was able to retrieve the ID of each video produced by the analyzed channels. Using this ID, I consolidated data on views, likes, comments, duration, title, and publication date for each video, resulting in a large DataFrame with individual data for each video from the 3 analyzed channels.

## First look
I created a division based on the publication duration: 60s<= is categorized as Short, otherwise, the publication is classified as Live, and you can see the total number of posts for each channel by this division. 
![1](https://i.imgur.com/eOpOfI4.png)

In the next image, there is a total consolidated view count by publication type, showing which podcast currently has the highest number of views, and comparing it with its competitors, divided by publication type. 
![2](https://i.imgur.com/15bZeN0.png)

I created a measure to calculate the proportion of views per second of publication. 
![3](https://i.imgur.com/mNHaxjz.png)

## Flow
Charts of the number of posts, views, likes, and comments of Flow in timeline mode, followed by the chart showing the trend.

![4](https://i.imgur.com/l3EteIQ.png)

![5](https://i.imgur.com/vSpQ7dm.png)

![6](https://i.imgur.com/YqAGjcZ.png)

![7](https://i.imgur.com/ja3n0ui.png)

![8](https://i.imgur.com/HUnWrrq.png)

![9](https://i.imgur.com/LCVRHt2.png)

![10](https://i.imgur.com/ryRiLIq.png)

## Inteligência LTDA

Charts of the number of posts, views, likes, and comments of Inteligência LTDA in timeline mode, followed by the chart showing the trend.

![11](https://i.imgur.com/iyNFJxM.png)

![12](https://i.imgur.com/ToeDeE6.png)

![13](https://i.imgur.com/jL5TpBp.png)

![14](https://i.imgur.com/uMSLryX.png)

![15](https://i.imgur.com/g7AdrsV.png)

![16](https://i.imgur.com/RMZ82XN.png)

![17](https://i.imgur.com/sKO6mgb.png)

![18](https://i.imgur.com/C4nL32u.png)

## Podpah

Charts of the number of posts, views, likes, and comments of Podpah in timeline mode, followed by the chart showing the trend.

![19](https://i.imgur.com/4lOOM8x.png)

![20](https://i.imgur.com/xxnyzf8.png)

![21](https://i.imgur.com/M6eavs6.png)

![22](https://i.imgur.com/hRmGy6f.png)

![23](https://i.imgur.com/cfhcqJY.png)

![24](https://i.imgur.com/R3vEXZJ.png)

![25](https://i.imgur.com/vA8tUxm.png)

![26](https://i.imgur.com/KEv2GaU.png)

## Comparison between the three

At first glance, it seems that over time, Flow has been losing relevance compared to the other two competitors.

FLOW = Blue, PODPAH = Green, INTELIGÊNCIA LTDA = Orange

![27](https://i.imgur.com/dntLt0q.png)

![28](https://i.imgur.com/798hAmZ.png)

![29](https://i.imgur.com/M6pweHU.png)

![30](https://i.imgur.com/c2GIxNL.png)

![31](https://i.imgur.com/FM3AIZP.png)

## Flow Studios

It turns out that Flow cannot be analyzed solely by the Flow podcast channel, as they started expanding and creating the Flow studios. Below are the same previous analyses, but with the numbers referring to the Flow Studios as a whole.

![32](https://i.imgur.com/ROORZvv.png)

![33](https://i.imgur.com/YsPfGiF.png)

![34](https://i.imgur.com/fVyU8Wm.png)

## New comparison between Studios Flow and the other two

It can be observed in this new analysis that Flow Studios, as a whole, remains the podcast/network with the highest engagement in the field, although spending much more than its competitors, as the amount of content production is significantly higher. The following chart shows the consolidated publications between Flow Studios as a whole versus the other two competitors. At the end, you will find the comparisons in timeline mode.

![35](https://i.imgur.com/vkHTzhp.png)

![36](https://i.imgur.com/yUGIqQ1.png)

![37](https://i.imgur.com/05zErim.png)

![38](https://i.imgur.com/EfIHIJE.png)

![39](https://i.imgur.com/Ztx4JQ2.png)

![40](https://i.imgur.com/gZF8lah.png)

![41](https://i.imgur.com/ugq9hk5.png)

![42](https://i.imgur.com/Izy2Pa6.png)
