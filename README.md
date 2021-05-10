# webscraping-using-lambda-and-node-js

### Setup

* Clone this repo:
*

1. The code is written on aws lambda using node js 
2. You will Need to add the Cheerio and request package from the npmjs.com and install it on your local machine and then you will need to zip all the folder and add it to the layers of the aws lambda.
3. You will need to configure the test event and set the execution time to 5 seconds with the parameters given below:

Dont forget to add the https or http before adding the domain
   ```
   {
   "url":"https:www.youtube.com" // you can add any domain you want
   }
   ```
4. Give a name to the test event that you have created.
5. then just deploy the changes and click on test   
