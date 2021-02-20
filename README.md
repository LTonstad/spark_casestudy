# Spark Case Study

## Goals:

* To look into the activity on tweets in relation to the potentially sensitive flags as well as mentions of the candidates within the content of the tweets

## Visualizations:

First a spark.sql query was ran to get information on potentially sensitive tweets:

![query](./images/kyle_query)

One of the first thing that interested us in the data is the potenially_sensitve label that a portion of the tweets tagged True:

![Sensitive per day](./images/sensitive_daily)

We took a look at the Tweets over From Wed 26 to Fri 29 of 2017, you'll notice the y-axis is much larger in this screenshot below:

![Sensitive compared to total](./images/sensitive_to_total)

Another thing that we looked into was the presence of the candidates names within the text of the tweets:

![Counts on candidates](./images/Henry2)

Then to get a look at the amount of retweets per candidate:

![counts](./images/candidate_counts)

Shown in a graph

![retweets](./images/candidate_retweets.png)

And which countries had the most tweets in the dataset:

![countries](./images/tweets_percountry.png)

## Potential future ideas

* A look into potentially sensitive retweets/favorites over time
* Using the coordinates to map out where the tweets were coming from
