# Heroku-Rapidleech

`git clone https://github.com/HasibulKabir/Heroku-Rapidleech`

`cd Heroku-Rapidleech`

`heroku login`

`heroku git:remote -a xxxxx`

`heroku stack:set container`

`git push heroku HEAD:master --force`

#### Optional:

`heroku ps:scale worker=0`

`heroku ps:scale worker=1`
