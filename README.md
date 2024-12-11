# Spotify-Analysis---AWS-Data-Engineering-Project
Leveraged ETL Data Engineering pipeline on AWS 


An exciting project using AWS services to process and analyze a Spotify dataset from Kaggle, which contains detailed information on albums, artists, and tracks. This project was a deep dive into the powerful capabilities of AWS for building scalable data pipelines and performing data analytics.
1. Beginning with setting up the necessary IAM roles and permissions to ensure secure access and management of AWS services throughout the pipeline, then created an S3 bucket to serve as a staging area, where I stored the raw Spotify data for further processing.
2. Leveraging AWS Glue, I designed and implemented ETL pipeline to transform and clean the data, preparing it for deeper analysis. This involved organizing the data into a structured format, handling missing values, and performing other necessary transformations which included joins.
3. Furthermore, automated data discovery and cataloging in AWS Glue Crawler which allows users to seamlessly query the data using AWS Athena, and perform additional transformations and analyses through SQL.
4. With Athena, I was able to uncover deeper insights into the dataset, such as track popularity trends, artist performance metrics, and genre-based comparisons.
5. The final step of the project was creating a dynamic, interactive dashboard using QuickSight.
6. The dashboard visualizes - 
  * Identifying the top N tracks and understanding how the popularity varies based on the duration of the track. 
  * Determining the labels associated with the popular albums
  * Recognizing the best artists and displaying the summary of each artist along with their performance against their target on request.
Overall, this project was a rewarding experience, allowing to sharpen skills in cloud-based data engineering and work with some of the most powerful tools in the AWS ecosystem.

