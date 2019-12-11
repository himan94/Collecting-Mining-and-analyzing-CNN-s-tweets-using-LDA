# Collecting/Mining and analyzing CNN's tweets using LDA

The steps involved are:

- Developing a script in python to automate the collection of tweets from twitter. As twitter has recently changed it's privacy policy and   hence restricts the api from operating for more than 15 mins/2000 tweets, the script manually puts the system to a halt after every 15     mins and restarts again after another 15 mins.

- After collecting the tweets, Regular expression (RE) was used in python to clean/wrangle the data. In addition to this, stemming and       lematization were also performed.

- The next step involves the use of Latent Dirichet Allocation(LDA) to find the topic of the tweets . LDA is a clustering algorithm which     also provides the critical words associated withh the topic.

- To showcase the result of the analysis, plots were developed using d3 and javascript.

For viewing the code please check the ipynb file

For viewing the insights as well as the business questionsplease check the report
