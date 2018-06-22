*Google Cloud BigQuery Part :

I downloaded the CSV File for Popular Tweets in My Country Egypt using my Twitter API on my Personal Twitter Account .
Upload the CSV Data File for the Tweets on Google Cloud BigQuery for Storage (i made a job to write the Result Files on Google BigQuery but it failed so i skip this part , and used my Bucket Instead on Google Cloud Platform)   
It Detected the Scheme and Created the Table based on this CSV File .
I can Query on this Data using SQL Scripts to view Data like:

Select * from [Twitter.Twitter_UserTweets] --The Main CSV File that i used on ETL DataFlow, Storage and Google DataStudio  
Select * from [Twitter.Twitter_t]           

Note :
I tried to share the BigQuery Part and DataSet with Everyone and get a link but i couldn't
Thanks to Provide account to add him to View this Part

*Google DataFlow Part :

I Created a Bucket Folder Called "mindvalleytask" on this Link "https://console.cloud.google.com/storage/browser/mindvalleytask"
Link for gsutil : "gs://mindvalleytask"
Then i Created a Project Called "My First Project" Then i added a Pipline Extract Job "tweets-words-count" to get the the words from the tweets and count of the occurrences of each word
The Extract Phase was Extract the Data from my Bucket with the Twitter Data
The Transformation Phase was to get the the words from the tweets and count of the occurrences of each word which is Done Successfully  as i checked the output Txt files that Coming from the ETL DataFlow Process
I refreshed the Storage Bucket and i found the Result file on Path : gs://mindvalleytask/user-tweets-results
Below Three Result Files :
user-tweets-results-00000-of-00003
user-tweets-results-00001-of-00003
user-tweets-results-00002-of-00003
This three files show the count of the occurrences of each word in this file --all files Attached

Then i loaded the Result files to the Google Cloud Platform using Google DataFlow

Note :
I tried to share the DataFlow Project Part and the used Bucket with Everyone and get a link but i couldn't
Thanks to Provide account to add him to View this Job 
 
*Data Visualization and Analytics Part :

Report Avaliable on below Link :
https://datastudio.google.com/open/1FGf81wD7xBhQjCjwng5U30I1yMFlcjJ-

The Report is (Public) and Anyone has this link can see the report
I used Google DataStudio for Data Visualization 
I tried to connect to the Three result files on google Clout Platform but i could't find how
So i made Data Visualization and build my Dashboard on the Original Table Created on Google BigQuery
I Build my DataSet on Table [Twitter.Twitter_UserTweets] that Created before on Google BigQuery 
Then
I made some Aggregations on the Fields and used most of Avaliable Graphs, Charts, Tables and  Filteration to Visualize my work as Screenshots attached


*I uploaded the CSV Files , the Txt Result Files and Screenshots for all the Project Phases on GitHub .
Link : 
https://github.com/AhmedMagdyAli/Mindvalley-DataEngineerTask.git

please don't hesitate to Contact me if you or the Team leader needs any more Discussion 

*Throught the whole Project i was Consider the Health of the Google Running Services
also please note this is my first Impact with all Google BI Tools and GitHub also


Thanks 

Ahmed Magdy Ali
Senior Business Intelligence Specialist