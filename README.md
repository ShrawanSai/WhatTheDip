# WhatTheDip

**This project aims to achieve the following**

1) Create a dashboard that allows you to monitor/watch a particular stock.
2) Highlight major dips and rises in the stock
3) Trace back reasons to what might have caused the dip by monitoring social media feeds
4) See if notable relationships (in tyerms of stock fluctuations) can be established between various stocks and various social media entities
5) Send in notifications when related trends in social media might affect stock prices
---

## **Approach**
 - Parse relatable Articles and information sources on these stocks (and the industry they're related to) and create a knowledge graph from the same
 - Try to establish a relationship between every node of the knowledge graph and current trending topics from streaming social media feeds with popular hashtags, news updates/articles etc by looking for indirect connections through wikipedia, historical connections from news articles, trending social media posts etc

## Example

#### Let's take **Airtel**

Consider the text about Airtel

> Bharti Airtel Limited, also known as Airtel, is an Indian
> multinational telecommunications services company based in New Delhi,
> India. It operates in 18 countries across South Asia and Africa, as
> well as the Channel Islands. Airtel provides 2G, 4G LTE, 4G+ mobile
> services, fixed line broadband and voice services depending upon the
> country of operation. Airtel had also rolled out its VoLTE technology
> across all Indian telecom circles. It is the second largest mobile
> network operator in India and the second largest mobile network
> operator in the world with over 457.96 million (45.796 crore)
> subscribers. Airtel was named India's 2nd most valuable brand in the
> first ever Brandz ranking by Millward Brown and WPP plc.
> Airtel is credited with pioneering the business strategy of
>        outsourcing all of its business operations except marketing,
>        sales and finance and building the 'minutes factory' model of low
>        cost and high volumes. The strategy has since been adopted by
>        several operators. Airtel's equipment is provided and maintained
>        by Ericsson, Huawei, and Nokia Networks whereas IT support is
>        provided by Amdocs. The transmission towers are maintained by
>        subsidiaries and joint venture companies of Bharti including
>        Bharti Infratel and Indus Towers in India. Ericsson agreed for
>        the first time to be paid by the minute for installation and
>        maintenance of their equipment rather than being paid up front,
>        which allowed Airtel to provide low call rates of ₹1 (1.4¢
>        US)/minute."

**The knowledge graph for this text would look something like this**

![image](https://user-images.githubusercontent.com/36449863/126386673-f6af5bdb-ec9d-4494-acec-1c6a35b92c70.png)



#### At the time of editing this README file,  *Richard Branson*'s trip to space was trending. 

Here is one of the trending tweets from then 

![image](https://user-images.githubusercontent.com/36449863/126387711-a741d07d-e28b-46c1-8f33-4e36e4cb1a3b.png)

**Let's take Richard Branson as sample trending topic**

### Now we would try establishing a meaningful relationship between Richard Branson and all nodes in our Knowledge graph.

That is 

> **Richard Branson** 
> &
> (Bharti Airtel Limited, New Delhi, South Asia, Airtel,	Line G operation, Indian telecom circles, etc)
---

### To establish relationships, one way could be connecting the *Wikipedia* pages of both.

 - If we try reaching establishing a connection between Bharati Airtel and Branson with Wikipedia, here is one possible connection
 
![image](https://user-images.githubusercontent.com/36449863/126388941-c49e7c61-85c9-41db-a6ce-86f337fa320a.png)

Hmm. Seems like a good possible connection

 - Connecting Branson and Airtel India gives us this
 
![image](https://user-images.githubusercontent.com/36449863/126392961-94b1914b-e4cc-48d0-b3eb-3542a0b6e2d1.png)


Well that is a handful. Most of these are not of much use
However, If you look at this particular relation, 
![image](https://user-images.githubusercontent.com/36449863/126392552-735a1951-cb32-47f0-9c3b-43d2a19cdef6.png)

This actually makes a lot of sense. 

You see, Richard Branson owns the Virgin group and pretty recently, this happened.
![image](https://user-images.githubusercontent.com/36449863/126392494-d7d831b5-4bb0-42b0-8ffd-e80effa4e79a.png)

Furthermore, 
![image](https://user-images.githubusercontent.com/36449863/126392814-81ebd379-364b-4491-a70e-54267e95462d.png)

It is a longshot but there seems to be a pretty solid **connection between Airtel and Branson.**

## Alright so it seems Richard Branson and Airtel have some indirect relation. So what?

### Well now we have to see if maybe Branson in any way has any affect in Airtel's stock market.

### Let's check it out

Last year Branson got some attention during the pandemic.

![image](https://user-images.githubusercontent.com/36449863/126393720-03dc1859-7789-4b86-afeb-6c7653190ac7.png)

This was around the **last week of April Last year**. According to me, it seems clear enough that the virgin group had some tough times back then.
And it so happened to be that there was a **slight dip in the Bharti Airtel Ltd stock** around the same time.

![image](https://user-images.githubusercontent.com/36449863/126398080-fae45dee-eb02-449a-9249-90b09ceb3ae8.png)



**Coincidence? Yep it may very well be one.** 

But here is another case.
Branson has been trending with regards to his trip to Space for quite a few weeks now.
It's been almost a week since he finished his trip.

Here is how the stock market faired in this period.

![image](https://user-images.githubusercontent.com/36449863/126395840-1dbd13f9-4100-42b4-8086-987db23c7242.png)

In both cases, it's so been the case that when Branson does well, So does Airtel. There could at least have been a minor affect.

It is very possible that both of these may have been coincidences. And to verify this, would be a long tedious task.

Automating this procedure (with more such cases) so that the hypothesis that Branson has some sway over how Airtel fairs is the secondary part of this project.

> Note: I am in no way saying that this is an actual relation that works. it's just an example lol


