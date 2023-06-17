# Overview 
This repository contains a sample function for deploying into Google Cloud Functions using a Cloud Build Pipeline. 

## Repository contents 
- function
---| Hello World function code
- cloudbuild.yaml 
---| Build Steps to deploy function coee 


## Notes 
## To manually submit a build, run the following, updating region, config, and source directory as needed
`gcloud builds submit --region=$REGION --config $CONFIG_FILE_PATH $SOURCE_DIRECTORY`