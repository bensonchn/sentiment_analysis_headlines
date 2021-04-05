# sentiment_analysis_headlines

## What does it do?
This scrapes each headlines news for the desired stock on the following website: finviz, marketplace, google news, and applies Vader to find an overall sentiment of the given day based on all the headlines given by the website and then shows a graph

## How do you read the graphs?
The scores are between 1 and -1 on the y-axis.

The closer to 1 the better, and vice versa.

## Conclusion 
In this test, I found that different website will not have the exact same news: news might be missing but with three different websites we can overall assess a feeling of what the market might feel. We can also assess if the website may have biases¶

## For example on March 5, 2021: 
On finviz, we have all three tickers upto a certain date. But netflix has strong reportings everyday.

![image](https://user-images.githubusercontent.com/25267825/113550224-bb166a80-95c0-11eb-99ce-81a6b5bab4d8.png)

On marketwatch, we are missing a lot of tickers for each day. But we noticed that on 2021-04-03 there has been a negative report on amazon, but that was not reported on finviz

![image](https://user-images.githubusercontent.com/25267825/113550417-0597e700-95c1-11eb-8ebf-b87b2e659207.png)

On google news we have a lot more data, and we can see that Google has many (3) negative headlines that were not reported on the other news website

![image](https://user-images.githubusercontent.com/25267825/113550498-26603c80-95c1-11eb-8124-0441bf7db360.png)


## For example on Feb 14, 2021: 
On MarketWatch, there is no Amazon or NFLX for Feb 14, 2021. And the negative reporting for Google is much worse than the reporting on finviz.

![image](https://user-images.githubusercontent.com/25267825/113550071-7559a200-95c0-11eb-847b-4eee8763fa41.png)
Whereas on FinViz, we have all three companies

![image](https://user-images.githubusercontent.com/25267825/113550091-80accd80-95c0-11eb-9d5d-af4c0aecd4e7.png)

