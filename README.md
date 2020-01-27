# MongoDB-Lesson-1
ManogoDB Lesson 1 for Hack Your Future ***Class12***

## MongoDB not RDBMS

## Not a Transactional DB (You can not be sure that the data is not changed from other sources while you update it)

## Data is saved in JSON format but in Binary not Text, BSON (Bee-SON)

```
{
    "firstname": "Peter",
    "lastname": "Membrey",
    "numbers": [
        {
            "phone": "+852 1234 5678"
        },
        {
            "fax": "+44 1234 565 555"
        }
    ]
}
``` 

## There are no tables vs. RDBMS which has a static design 

## installing MongoDB

[Download] (https://www.mongodb.com/download-center/community)

1. Select the zip version
2. Unpack to c:\MongoDB
3. Open a command prompt
4. Starting the server Run c:\MongoDb\bin\mongod.exe
5. Open a command prompt
6. Run c:\MongoDB\bin\mongo.exe

## Basic commands

Table 2-2: Basic Commands within the MongoDB Shell
Open table as spreadsheet

|Command|Function|
| ------------- |-------------|
|show dbs|Shows the names of the available databases.|
|show collections|Shows the collections in the current database.|
|show users|Shows the users in the current database.|
|use "db name"|Sets the current database to <db name>.|
