cd Documents/Dev/git/portfolio/

express noahportfolio
cd noahportfolio && npm install

DEBUG=noahportfolio:* npm start

heroku app:create noahportfolio
heroku git:remote –a noahportfolio
git push heroku master
heroku ps:scale --app noahportfolio web=1

