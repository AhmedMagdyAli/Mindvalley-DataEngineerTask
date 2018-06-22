*Google DataFlow Part :

I Created a Bucket Folder Called "mindvalleytask" on this Link  :"https://console.cloud.google.com/storage/browser/mindvalleytask"
Link for gsutil : "gs://mindvalleytask"
Then i Created a Project Called "My First Project" Then i added a Pipline Extract Job "tweets-words-count" to get the the words from the tweets and count of the occurrences of each word
The Extract Phase was Extract the Data from my Bucket with the Twitter Data
The Transformation Phase was to get the the words from the tweets and count of the occurrences of each word which is Done Successfully as i checked the output Txt files that Coming from the ETL DataFlow Process
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