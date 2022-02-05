# Deploy fastAPI to Heroku using Docker

[FastAPI](https://fastapi.tiangolo.com/) Modern, fast, web framework for Python  
[Docker](https://www.docker.com/) Containerization software  
[Heroku](https://www.heroku.com/) Hosting platform

## Requirements

[Git](https://git-scm.com/) (or just download the repo)  
[Heroku cli](https://devcenter.heroku.com/articles/heroku-cli) (to run the heroku commands)

## Instructions

Note: Replace `your-app-name` in the instructions with the name you wish to have on your app.

1. Install git (or just downlad the repo)
2. Install [Heroku cli](https://devcenter.heroku.com/articles/heroku-cli) and [log in](https://devcenter.heroku.com/articles/heroku-cli#getting-started)

3. Clone or download this repo.

```bash
git clone https://github.com/askblaker/fastapi-docker-heroku.git
```

4. cd into the directory

```bash
cd fastapi-docker-heroku
```

5. Create the heroku app

```bash
heroku create your-app-name
```

6. Set the heroku cli git remote to that app

```bash
heroku git:remote your-app-name
```

7. Set the heroku stack setting to container

```bash
heroku stack:set container
```

8. Push to heroku

```bash
git push heroku main
```

9.  Enjoy your fastAPI app at [https://your-app-name.herokuapp.com](https://your-app-name.herokuapp.com)
