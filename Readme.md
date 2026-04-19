#Learning the Backend Series

This is a video series on backend with javascript

git cmds:
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main

this cmd is useed to create nodemon to start & stop the server
cmd:> npm i -D nodemon

after this update hte script in the package.json
"scripts": {
    "dev":"nodemon src/index.js"
  },