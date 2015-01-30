---
layout: post
title:  Continous Integration and Continous Deployment with Node.js and AngularJS
---

# {{ page.title }}

*XX Oct 2014 - Stockholm, Sweden*

*intro...*
A course over at [Pluralsight](http://www.pluralsight.com/courses/continuous-integration-deployment-angularjs-nodejs) by [Alexander Zanfir](https://twitter.com/alexzanderzan).

Heroku

### Cloud9

### Node.js, npm, bower

npm init
npm install --save express
npm install --save jade
npm install --save-dev bower

bower init
bower install jquery --save
bower install angular --save
bower install bootsrap --save


### Jade and AngularJS
Pythonic-ish html

### Heroku
`git init`

`git add`

`git commit`

`heroku login`

`heroku create`

`git push heroku master`

`heroku ps:scale web=1`

### MongoDB
mongoose
create/connect
schema

```javascript
var jobSchema = mongoose.Schema({
    title:{type:String},
    description:{type:String}
});
```

Mongolab...
<https://mongolab.com/>
### Testing

mocha and chai


## js

asynchrounus calls and nested callbacks - bluebird; helps deal with exceptions and errors

Use Promise/bluebird to get a readable story, to get rid of the nested callbacks.

x.then() replaces anonymuos x.exec(function())

```javascript
var Promise = require("bluebird");
```

bluebird is a fully featured Promise library, with good performance.

### Further reading
* pluralsight
* [Package Managers; npm and bower](http://tech.pro/tutorial/1190/package-managers-an-introductory-guide-for-the-uninitiated-front-end-developer)
* <>
