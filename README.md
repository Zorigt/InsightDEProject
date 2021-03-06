# Career Match
## Project Idea
Build an open source pipeline to explore the essential skills preferred for a job posting and match with candidates with most relevent skill set.
## Purpose
Nowadays the technology advances blazingly fast. The tools/skills popular yesterday may not be preferred tomorrow. Also sometimes titles in a job posting could be confusing: a Data Engineer position could be titled as Data Analyst, or Data Scientist, or Software Engineer, etc. It is worthwhile to use the weapon of big data to find out the important relevent skill for a certain job. 
## Use Case
* Find out the most relevent skills for a certain type of job
* Find out the trend of companies hiring patterns over different job positions/teams
* Recommend the candidates with most relevent skill set to a open job position from a company 
## Technology Considered
* Data Storage Layer: Common Crawl, AWS S3
* Data Ingestion Layer: Elastic Search, Kafka
* Streaming Process: Kafka, Flink
* Bash Process: Spark
* DataBase: Canssandra
## Pipeline Architecture
![alt text](/architecture.png)
