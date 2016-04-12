#Webpack-Express-Angular
Boilerplate app for deploying Angular apps to [Heroku](https://www.heroku.com/)

##Stack:
- [Webpack](http://webpack.github.io/) (with Hot Module Reloading)
- Express
- ES2015 (transpiling with [`babel`](https://babeljs.io/))
- Angular 1.5 (component based architechture and `ui-router`)

##Installation
1. `npm i`
2. `webpack`
2. `npm start`
3. Open browser to `localhost:3000`

##Deployment
1. In `.gitignore`, remove `dist/bundle.js`
2. Git commit
2. Create your Heroku app and `git push heroku master` 

This is meant to be as bare-bones as possible, allowing you to add your own testing, linting, CI, CD, or an endless amount of other options...
This is born out of the struggles of the modern development process, hopefully allowing you to focus more on building versus tooling.
Create an issue or pull request if there is something you'd like to see/add
