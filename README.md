Heroku Example
==============

# Repositorio GitHub
- 1) git init
- 2) git add .
- 3) git commit -m "..."
- 4) git push origin master

# Repositorio Heroku
- 0) Con el repo GitHub ya creado ..
- 1) heroku login
- 2) heroku apps:create AppName
- 3) git push heroku master
- 4) heroku config:set NODE_END=production

# Otros comandos Heroku & Git
- 1) heroku restart
- 2) heroku open
- 3) heroku logs
- 4) git remote add  heroku git@heroku.com:your_app_name.git
- 5) git remote -v

#
URL example :: http://mean-example.herokuapp.com/
