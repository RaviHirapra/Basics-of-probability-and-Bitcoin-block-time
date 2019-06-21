# Basics-of-probability-and-Bitcoin-block-time
New bitcoin blocks are mined at every ten Minute. Or is it? If you look at the [time stamps](https://blockstream.info/block/00000000000000000013a0d4f0239b9908928eaf3e6243fa02d7a67b98ce045f) of blocks, you will hardly find two blocks mined exectly ten minutes apart. Some times it takes just few second while sometimes it takes more than an hour to find a new block. But if you take an average over a month it will be very close to 10 minutes. Let's we see how this happens.

In Bitcoin, it takes on average 10 minutes to mine a block. Here are some questions I will try to answer:
Q1 - Is it is possible that sometimes a block will take 20 minutes to mine? What about 1 hour? What are the chances that two blocks are mined just one second apart? We need some basics of probability to answer these questions.

## Basics of Probability:
What is probability? When there are possible outcomes in an experiment, we can assign a number to each outcome based on how likely it will happen. The total sum of all assigned number must be 1.

Let's say your experiment is tossing a coin. Since it is equally likely that either Head or tail will appear, we give 0.5 probability for Head and 0.5 for the tail. Sum of the probability of all possible outcomes must be 1.

#### Few more example:
* Let say you throw a fair dice. Since there are 6 possible outcomes from 1 to 6, and all are equally likely, we have 1/6 probability for each number from 1 to 6 in this experiment.

* Let's say I toss a coin two times. If I use notation HT for 'first apeard Head, second apeard Tail', then all possible outcomes are HH, HT, TH and TT. What is the probability that I will get at least one head? As three outcomes out of four have at least one head, the answer is 3/4 = 0.75 = 75% chances.

* Let's say I throw a dice twice. What is the probability that I will get 10 as a sum on their faces? Here we need to find all possible outcomes and all those outcomes which give 10 as a sum. There are 6*6=36 possible outcomes. Let we use the notation (1,2) for 'first dice gave 1 and the second dice gave 2', then below is all 36 possible outcomes:

    (1,1), (1,2), (1,3), (1,4), (1,5),(1,6), (2,1), (2,2), (2,3), (2,4), (2,5), (2,6), (3,1), (3,2), (3,3), (3,4), (3,5), (3,6), (4,1), (4,2), (4,3), (4,4), (4,5), (4,6), (5,1), (5,2), (5,3), (5,4), (5,5), (5,6), (6,1), (6,2), (6,3), (6,4), (6,5), (6,6)

    Only three of them out of 36 gives you sum as 10, which are (4,6), (5,5) and (6,5). Thus the probability that you will get 10 as a sum 10 while tossing two dice is 3/36 ~ 0.0833 ~ 8.33% chances.
    
#### Little bit advanced probabilty

If I toss a coin 10 time what is the probabilty that I will get HTHTHTHTHT

WORK IN PROGRESS

----
In Bitcoin, It takes on average every 10 minutes for a block to mine. Lets we assume that block propagation time is zero and once the block is reached to all other miners, it takes zero amount of time to verify the block. This assumption will make modeling simple. Since 10 minutes is way bigger than a few hundred milliseconds (the time it takes to propagate and varify a block), this assumption will not affect our modeling that much. 
We can think of a hash as a huge dice with a large number of faces. 


 A hash computation is solves the 


Let's P is the probability that a block will be mined in one second. We assume that the total hases calculated by all the miners per second is nearly constant. 
Now
