# flaskDeployment


git init
git add .
git commit -m "Initial commit"


wget -qO- https://cli-assets.heroku.com/install-ubuntu.sh | sh

heroku login

heroku local web

git push heroku master

