# Twitter_Data_Pipeline_Using_Airflow


Using Twitter Developer API & Tweepy Library ----- Get the Data using tweepy function -- [data is in json Format ] -- uson Json Library to find the relevant data and convert dat

data to the list ---> save this file using pandas dataframe to S3 using s3fs library --[[ This whole is the ETL Process]]


Now we will implement the same using Apache Airflow

Start the EC2 instannce on AWS --[ Allowinig for the http and https traffic to come]  and using linux  run the bash command to install the dependcies on the system
then install airflow
-- create a dags folder and configure the airflow config file to load the dags from our defined location

-- created a dag using DAG and  using Python Connector run our python commands.
