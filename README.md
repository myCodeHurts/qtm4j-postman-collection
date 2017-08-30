# qtm4j-postman-collection

Postman Collection contains HTTP requests for uploading test result file on JIRA instance using [QMetry for JIRA - Test Management](https://marketplace.atlassian.com/plugins/com.infostretch.QmetryTestManager/cloud/overview).


### JIRA Cloud

Import automation test result to QMetry for JIRA is 2 step process. 
1. Get file upload URL
2. Upload you test result file to URL generated in Step 1

#### Steps to follow

1. [Download](https://www.getpostman.com/) Postman app if you don't have. 
2. [Import](https://www.getpostman.com/docs/postman/collections/data_formats) this collection in your Postman App. 
3. In first HTTP request provide your details. For more info about request params refer [QMetry docs](https://qmetrytestdocs.atlassian.net/wiki/).
4. In second request, select your test result file. 

#### Run Collection

Once you fill request params and upload file, its time to run this collection. 

You have 2 options. 

1. You can run POSTMAN collection directly. [Like this](https://www.getpostman.com/docs/postman/collection_runs/starting_a_collection_run)
2. Or you can run each request seperately. After 1st request is completed, copy URL from response and put as request URL in 2nd request. 
