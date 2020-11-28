# Deploying dockerized fastAPI to Heroku 

[FastAPI](https://fastapi.tiangolo.com/)
[Docker](https://www.docker.com/)
[Heroku](https://www.heroku.com/)

1. Clone this repo. Set up and push to heroku.

```bash
git clone git@github.com:askblaker/fastapi-docker-heroku.git
cd fastapi-docker-heroku
heroku create <your-app-name>
heroku git:remote <your-app-name>
heroku stack:set container
git push heroku main
```

2.  Enjoy your fastAPI at https://your-app-name.herokuapp.com
