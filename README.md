<h2>Overview</h2>
As the capstone project for the Udacity Data Scientist Nano-degree program, I worked on a 12 GB of consumers logs of a music streaming app called sporkify. The data iss available on the AWS S3 buckets to the public through "s3n://udacity-dsnd/sparkify/sparkify_event_data.json". A subset (128MB) of the full 12 GB of dataset is also available though "s3n://udacity-dsnd/sparkify/mini_sparkify_event_data.json". I developed a python (in Pyspark kernel) code and used spark to explore, clean and analyze the big data to create a model to predict the possible future unsubscribers of the music streaming app. I uploaded the notebook on the EMR cluster that I created on AWS.
The EMR cluster had 4 instances(1 master and 3 core nodes) of m5.xlarge type. 


