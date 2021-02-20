# Spark Case Study

First a spark.sql query was ran to get information on potentially sensitive tweets:

![query](./images/kyle_query)

One of the first thing that interested us in the data is the potenially_sensitve label that a portion of the tweets tagged True:

![Sensitive per day](./images/sensitive_daily)

We took a look at the Tweets over From Wed 26 to Fri 29 of 2017, you'll notice the y-axis is much larger in this screenshot below:

![Sensitive compared to total](./images/sensitive_to_total)

Another thing that we looked into was the presence of the candidates names within the text of the tweets:

![Counts on candidates](./images/candidate_counts)
