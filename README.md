# ai-speech-translator
Users can transcript audio files into a text file using this website.
replace your subscriptionKey and serviceRegion to index.js file.

Step 1: Register the Speech Cognitive Service
Open the Azure portal and go to the “Create a resource” section and search the “Cognitive Service”
Create a new Cognitive Service, select the require “Subscription” and “Resource Group”.
Type the App “Name” as you required and provide the “Region” with Standard S0 “pricing tier” for free.
At finally tick the check box then click the “Review +Create” button, after validation passed clicked the “Create”

Step 2: Building the SpeechText Web App
Create an empty directory name as SpeechTextApp and now go to root terminal of project and initiation of node project with the below command.
Fill out the required information for the initialize of the project.
Create a file named index.js — this file will have the main code for our application.
After initiation of the node app, Now we’ve to installing the required below packages for this project.

Step 3: Run the app
Now the app is ready for a run.
Open the terminal from the root of directory and run the below “command”

Step 4: Deploy in Azure as a Web Service
As we’ve build & tested our app, now has time to deploy the app through Azure App Service.
Open the Azure Portal and create an app service for the node environment.

