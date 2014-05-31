mathisonian-autopages
============

mathisonian's server for [autopages](/mathisonian/autopages).

## about

* fork this repo and put your repository in app.js
* push to heroku
* ???
* your github pages will update automatically

```
'use strict';

var Autopages = require('autopages');

var autopages = new Autopages(process.env.GITHUB_KEY);


// update this line!
// autopages.register('your/repo');

```


### more details

* When pushing to heroku make sure to set the following environmental variables
  * `URL` - the url of the heroku instance (no trailing slash)
  * `GITHUB_KEY` - a github api key with push access to your repo and its webhooks
