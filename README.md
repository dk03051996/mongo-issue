# mongo-issue
Evrything related to mongodb


mongodump and mongorestore are very useful commands to copy the data or migrating the data.
If you are migrating the data from local to any you can use this command or if you want to copy the data from any EC2 to local you can use this command

mongodump -h sample.mongodbhost.com:27017 -d DATABASE_NAME -u USER_NAME -p SAMPLE_PASSWORD -o ~/Desktop  
