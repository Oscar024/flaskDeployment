# flaskDeployment


git init
git add --all
git commit -m "Initial commit"

pip install gunicorn

pip freeze > requirements.txt

git add --all
git commit -m "requirements"

#Create a Procfile without extention

git add --all
git commit -m "Procfile"

#Create a runtime to specify Python version
git add --all
git commit -m "runtime.txt"


#If you do not have heroku CLI, for ubuntu:
wget -qO- https://cli-assets.heroku.com/install-ubuntu.sh | sh

heroku login

heroku create

heroku local web

git push heroku master

