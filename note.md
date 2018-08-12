
Responsive Portfolio

> npm init
> npm install node-sass

change `scripts` in package.json

  "scripts": {
    "sass": "echo \"Hello from SASS\""
  },

> npm run sass

then change it again:
(node sass watch scss output to dist folder as css)

"scripts": {
  "sass": "node-sass -w scss/ -o dist/css --recursive"
},

> npm run sass

> modern_portfolio@1.0.0 sass /Users/gloriading/Project/modern_portfolio
> node-sass -w scss/ -o dist/css --recursive

(start watching)
then code in main.scss, it will auto compile to dist/main.css
don't touch main.css , don't stop this


> touch .gitignore
> git init
> git add .
> git commit -m 'something'


> npm install gh-pages

{
  "name": "modern_portfolio",
  "version": "1.0.0",
  "description": "Responsive Portfolio Website",
  "main": "index.js",
  "homepage": "https://gloriading.github.io/modern_portfolio",
  "scripts": {
    "sass": "node-sass -w scss/ -o dist/css --recursive",
    "deploy": "gh-pages -d dist"
  },

> npm run deploy









<!--  -->
