# Project: *Gym - customer retention strategy*

<img src="" width="200" height="400" />

## Project description

The gym chain XY is developing a customer interaction strategy based on analytical data.

One of the most common problems gyms and other services face is customer churn. How do you know if a customer is no longer with you? You can calculate churn based on people who get rid of their accounts or don't renew their contracts. However, sometimes it's not obvious that a client has left: they may walk out on tiptoes.

Churn indicators vary from field to field. If a user buys from an online store rarely but regularly, you can't say they're a runaway. But if for two weeks they haven't opened a channel that's updated daily, that's a reason to worry: your follower might have gotten bored and left you.

For a gym, it makes sense to say a customer has left if they don't come for a month. Of course, it's possible they're in Cancun and will resume their visits when they return, but's that's not a typical case. Usually, if a customer joins, comes a few times, then disappears, they're unlikely to come back.

In order to fight churn, Model Fitness has digitized a number of its customer profiles. My task is to analyze them and come up with a customer retention strategy.

[Jump to the general conclusion](#general)

## Walktrough: 

Build a binary classification model for customers where the target feature is the user's leaving next month.

**Step 1.** Divide the data into train and validation sets using the train_test_split() function.



**Step 2.** Train the model on the train set with two methods:

  - logistic regression
  - random forest
  
**Step 3.** Create user clusters
Set aside the column with data on churn and identify object (user) clusters: standardize the data. Use the linkage() function to build a matrix of distances based on the standardized feature matrix and plot a dendrogram. Note: rendering the dendrogram may take time! Use the resulting graph to estimate the number of clusters you can single out.

**Step 4.** Train the clustering model with the K-means algorithm and predict customer clusters.

## General conclusion
<a id="general"></a>

We can see in cluster with the bigest churn rate that these clients mostly live near the gym, mean age value is the lowest in this group, they have the least additional charges. They don't come to the gym so often, and the came by their own initiative; they are not an emplyees of a aprtner company nor did they came through promo ticket. They don't spend too much time in the the group activities as well. I would call this groupy 'Lazy' because it seems they don't have a lot of motivation for working out even though they live near the gym, but they did make an effort to join the gym, without a hel of a friend or a company where they work. It would be wise to make a kind of an interview or ask them to to fill up a questionare where they could possibly express their needs.

The second cluster by the churn rate is the group that differentiate from 'Lazy' group is that they don't live near the gym, but they still spend more time in the gym than the lazy ones, they did not use the promo ticket but big part of them came as an employees of a partner company. Even though they have a membership discount they still have low additional costs. I would call this group 'Curious' because they come to the gym even the don't live near. It could be useful to offer some kind of promo, for example; if they bring 5 new friends to the gym, they get one month free of charge. Also, a questionare or some kind of interview would also help with these group of clients.

The third cluster by the churn rate are clients that live near, big share of them are employees of partner company, they came throught promo ticket and the spend more time in gym than users from previous clusters. They also have higher additional costs. churn rate for this cluster is around 0.25 so the don't leave as much. They feel comfortable living near and have discount as employees of a partner company. I would call this group Comfortable

Fourth cluster by the churn rate are clients that live near and a low share of them came through partner company or by promo ticket. Their average additional costs are second highest, they spend the most time in the gym and they are the longest lasting members. Still, they don't make long period contracts with the gym. They are real gym Enthusiasts. It would be wise to show graditude to these clients and make a special gift or discount card.

Fifth cluster by the churn rate are clients that have the longest contract periods, on average around 11 months period. They have the highest additional costs, more than half of them enjoy group trainings. They live near and they are employees of a partner company. Around half of them came through promo ticket. Even though they have discount on membership and the spend the most money, they spend less time in gym than Enthusiasts. I will call them Committed because the plan to stay, considerig their long contract periods.
