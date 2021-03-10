* trying to figure out the minimal amount needed to deploy netcore to heroku
* using a heroku build back
* what is the least we need to do, so the buildpack works?
* will adding the app.json do it?
  * NO - this didn't work
All we need to do is set the buildpack to the url in the Settings
how do you set the port to listen on?
    * going to the heroku app url is getting 404
    * the example project works so we are missing something


Just use the project example that exists and remove things until it stops working du