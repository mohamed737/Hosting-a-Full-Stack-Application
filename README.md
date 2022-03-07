# Hosting a Full-Stack Application

app link is in applink.txt at the root folder

also documentaton folder is in the root folder

the screent shoots are in the root folder

running the karma test is in udagram-frontend folder npm run test


# simple diagram giving a high-level overview of the infrastructure

1-the forntend in udagram-frontend folder is built into www folder insid of it 
2-it is deployed to aws service called ---> s3

3-the backend in udagram-api folder it built into www folder
4-it is deployed to aws service called ---> eb
5-with its variables passed in ---> circleci 

6- the database used in the backend is ---> rds

#  diagram showing the overview of the pipeline.

the database is created with aws service called ---> rds 
the port host database name and password is passed to the backend in ---> circleci
the backend is built and deployed to ---> eb 
the forntend is built and deployed to ---> s3