community-autopages
============

community server for [autopages](/mathisonian/autopages).

## about

don't feel like hosting your own autopages server? use this one! 

* submit a pull request adding your repository to app.js
* give [autopages-bot](/autopages-bot) push access to your repo

```
'use strict';

var Autopages = require('autopages');

var autopages = new Autopages(process.env.GITHUB_KEY);


// update this line!
// autopages.register('your/repo');

```
