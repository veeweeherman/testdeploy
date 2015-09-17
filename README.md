Directions on how to deploy a Node/Express app in minutes:

1. First make sure you ahve the Heroku Toolbelt installed https://toolbelt.heroku.com/

2. Make a repo on Github

3. Clone down the repo locally

4. cd into the repo

5. npm install --save express

6. npm init

7. Fill in the blanks, and for "entry point" enter "server.js"

8. Copy and paste the contents of my server.js file into your own server.js file

9. create an index.html page, feel free to copy and paste mine

10. add a Procfile to the root level with the following text: web: node server.js

11. add a .gitignore file with: node_modules

12. git add, commit, and push to your origin master

13. in the terminal: heroku create _____ (where the blank is the name of the app that will be ____.herokuapp.com)

14. in the terminal: git push heroku master