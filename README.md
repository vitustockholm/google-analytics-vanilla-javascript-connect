# google-analytics-vanilla-javascript-connect

replace <'&lt;YOUR_CLIENT_ID>' with your client ID Google Analytics

Step1: Create a client ID

From the Credentials page:

   1. Click Create Credentials and select OAuth client ID.
   2. Select Web application for APPLICATION TYPE.
   3. Name the credential.
   4. Set the AUTHORIZED JAVASCRIPT ORIGINS to http://localhost:8080
   5. Set the AUTHORIZED REDIRECT URIS to http://localhost:8080/oauth2callback
   6. Click Create.


Step 2: Setup the sample

You'll need to create one file named HelloAnalytics.html, which will contain the HTML and JavaScript code for our example.

  1.  Copy or download the following source code to HelloAnalytics.html.
  2.  replace '<YOUR_CLIENT_ID>' with your client ID. created above.

Step 3: Run the sample

After you have enabled the Analytics API, and set up the sample source code the sample is ready to run.

  1.  Publish HelloAnalytics.html to your web server and load the page in your browser.
  2.  Click the Authorize button, and authorize access to Google Analytics.

When you finish these steps, the sample outputs the name of the authorized user's first Google Analytics view (profile) and the number of sessions for the last seven days. 
