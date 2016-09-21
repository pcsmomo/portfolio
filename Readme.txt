cd Documents/Dev/git/portfolio/

$ heroku app:create noahportfolio
$ heroku git:remote –a noahportfolio
$ git push heroku master
$ heroku ps:scale --app noahportfolio web=1
