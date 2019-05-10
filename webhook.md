# Set Up Webhook


* Go to the repository on GitHub where you would like to set up the automated out of office response, or create a repository to test this out.  (ie, `https://github.com/<USERNAME>/<REPO>

*  Make sure you are in the repo you would like the Out of Office reminder at, and click on the Settings tab. (ie, `https://github.com/<USERNAME>/<REPO>/settings


![reposettings](https://user-images.githubusercontent.com/2547497/57185999-fadfef00-6e8b-11e9-8fc8-147488ed820a.png)

* Under Settings, go to Webhooks, then click on the Add webhook button.


![webhookstab](https://user-images.githubusercontent.com/2547497/57186007-337fc880-6e8c-11e9-87b3-75ed946c2978.png)

   *The URL to get to this setting would be:*
      `https://github.com/<USERNAME>/<REPO>/settings/hooks`
      
      
* Set the Payload URL to the URL obtained when the project was remixed.  After the URL, add the path, `/hooks` to the end of the URL.
* Set the Content type to `application/json`.
* Set the Secret.  Remember this value.


![webhookpayload](https://user-images.githubusercontent.com/2547497/57186145-b73ab480-6e8e-11e9-99c0-750feb17d366.png)

* Select "Let me select individual events", and select "Issues".


![selectevents](https://user-images.githubusercontent.com/2547497/57186203-7a22f200-6e8f-11e9-9c38-37536977b633.png)

* Select the "Update webhook" button to save.
