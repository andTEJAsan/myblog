---
title: "Market Making Limit OrderBook"
date: 2024-07-30T17:15:58+05:30
draft: false
---
![Image](/img/lobook.png)

During the summer in kyoto I got the chance to participate in a simulated trading event called Trade-A-Thon organized by Optiver. 
It was an exciting event for me, as I learnt about market making and what an order book is. Upon seeing the simple UI of the platform on which the event was conducted I thought to myself that I should try building it, as it would be a good exercise for me to learn about orderbooks as well. 

If done properly, maybe I can also conduct trading events of our own in economics club at IITD!

I explored the following data structures for maintaining the order book :- heap and sparse array. In practice, sparse array might work as the prices are closely centered around a few values. 

[View the project on GitHub](https://github.com/andTEJAsan/LimitOrderBook)