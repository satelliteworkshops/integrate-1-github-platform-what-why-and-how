# Out-of-Office Responder on GitHub Using Octokit and Webhooks

<center>
   
![Surfing Dog](https://media.giphy.com/media/ToMjGpHwyUi7miO2LLi/giphy.gif)

</center>

- We will create an out of office responder when assigned issues on GitHub.
- A workshop exercise to demonstrate how GitHub webhooks work using [@octokit/webhooks](https://www.npmjs.com/package/@octokit/webhooks)and how we can make calls to GitHub using [@octokit/rest](https://www.npmjs.com/package/@octokit/rest)

## Pre-Work

Please do the pre-work prior to the workshop!

* Register an account on [**GitHub**](https://github.com/join?source=header-home) if you do not already have an account.
* Register with [**Glitch.com**](https://glitch.com/)
   - Can connect to the [Out of Office Skeleton project](https://glitch.com/edit/#!/remix/outofofficeskeleton)

### Obtain a Personal Access Token (PAT)
* Obtain a Personal Access Token by following these steps [here](pat.md)
   *You will need the Personal Access Token (PAT) value later.*
      
### Remix this project!
* Follow [these steps](remix.md).
*Remember what the URL is when the glitch project is remixed.*
   
**We will come back to setting up your glitch project after we set up the webhook!**


### Set up webhook
* Set up the webhook by following [these steps](webhook.md).
*Remember the secret you had set for the webhook.*

### Go back to Glitch project and set the .env file values.
* Click on the `.env` file.
   * Type in the secret you specified when setting up the webhook 
   * Set the Personal Access Token (PAT) value.  
   * Set the PORT value to `3000`.
   
   
   ![envfile](https://user-images.githubusercontent.com/2547497/57186284-6c6e6c00-6e91-11e9-941d-cba643f658f6.png)
   

