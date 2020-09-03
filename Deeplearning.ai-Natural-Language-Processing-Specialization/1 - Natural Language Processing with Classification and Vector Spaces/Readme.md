# Probability and Bayes’ Rule
* What are probabilities and conditional probabilities are?
* How they operate? 
* How they can be expressed mathematically?
* How to derive Bayes' rule from the definition of conditional probabilities? 

Bayes' rule is applied in many different fields ranging from medicine to education  and is used extensively in NLP. 

You can use it to  perform sentiment analysis on tweets.

Imagine you have an extensive corpus of tweets that can be categorized  as either positive or negative sentiment, but not both.  Within that corpus, the word happy is sometimes being labeled positive and  sometimes negative. 

## Why this situation is occurring?
one way to think about probabilities is by counting how frequently events occur. 

Suppose you defined events A as a tweet being labeled positive,  then the probability of events A shown as P of A here is  calculated as the ratio between the count of positive tweets and  the corpus divided by the total number of tweets in the corpus. 

In this example, that number comes out to 13 over 20 or 0.65.  You could also express that value as a percentage, 65% positive.  It's worth noting that the complementary probability here,  which is the probability of the tweets expressing a negative sentiment  is just equal to one minus the probability of a positive sentiment. 

Notes that for this to be true,  all tweets must be categorized as either positive or negative but not both. 

Let's define events B in a similar way by counting tweets containing the word happy.  In this case, the total number of tweets containing the word happy  shown here as N happy is 4. 

Here's another way of looking at it, take a look at the section of the diagram  where tweets are labeled positive and also contain the word happy.  In the context of this diagram, the probability that a tweet is labeled  positive and also contains the word happy is just the ratio of the area  of the intersection divided by the area of the entire corpus. 

In other words, if there were 20 tweets in the corpus and  three of them are labeled positive and also contain the word happy,  then the associated probability is 3 / 20 or  or 0.15.

