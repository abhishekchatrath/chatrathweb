Setup commands:

> create-react-app chatrathweb
> cd chatrathweb
> git init
> heroku create chatrathweb --buildpack https://github.com/mars/create-react-app-buildpack.git
> git add .
> git commit -m "Initial commit with buildpack"
> git push heroku master
> heroku open

This opened the heroku deployed website created in chatrathweb


Steps to update deployment:

1. See changes using "yarn start"
2. Commit changes using "git add ." and "git commit -m  "commit msg""
3. Push changes to heroku master "git push heroku master"
(NOTE: "git push" on its own at the time didnt work. Perhaps, can push to github too to save code online? Each time choose who to push to- heroku master or origin master)


Steps to switch between Github and Heroku:

Done...
> git remote add origin https://github.com/abhishekchatrath/chatrathweb.git
> 

Do...
0. Check changes using "yarn start"
1. Add changes "git add ."
2. Commit changes "git commit -m  "commit msg""
3. Push changes to Github "git push -u origin master"
4. Push changes to Heroku "git push heroku master"
