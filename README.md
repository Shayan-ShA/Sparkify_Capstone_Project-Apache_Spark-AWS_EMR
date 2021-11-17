<h2>Overview</h2>

As one of the capstone project of the Udacity Data Scientist Nano-degree program, I worked on a 12 GB of consumers logs of a music streaming app called sporkify. The data is available on the AWS S3 bucket to the public through "s3n://udacity-dsnd/sparkify/sparkify_event_data.json". A subset (128 MB) of the full 12 GB of dataset is also available though "s3n://udacity-dsnd/sparkify/mini_sparkify_event_data.json". I developed a python (in Pyspark kernel) code in Jupyter Notebook and used spark to explore, clean and analyze the big data. Then I created a model to predict the possible future unsubscribers of the music streaming app. I uploaded the notebook on the EMR cluster that I created on AWS.
The EMR cluster had 4 instances(1 master and 3 core nodes) of g4dn.2xlarge (an accelerated computing instance) type. 


[This](https://aws.amazon.com/ec2/instance-types) is the link to the features of the EC2 instances.


I started working on the subset(128 MB) of the full data to explore the data with spark local mode and pandas dataframe. Then I used the code to created a ML model to perform the training on AWS EMR notebook.

<h2>File description</h2>
<p>Notebook_Subset.ipynb is the notebook created to work with the subset of data.</p>
<p>Notebook.ipynb is the notebook created to work with the full data on AWS EMR Notebook.</p>


![Certificate.PNG](https://github.com/Shayan-ShA/Starbucks-Capstone-Challenge/blob/main/Certificate.PNG)

