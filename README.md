# On The Docs web app

This is a web app based on the [LINE Login starter application](https://github.com/line/line-login-starter) and hosted with [Heroku](https://www.heroku.com/).

Demo: https://on-the-docs-web.herokuapp.com/

## Quick start on Heroku

1. Use the "Deploy to Heroku" button to deploy the app

### Working with the app locally

1. Clone the repository to your local machine: [git@github.com:line/line-login-starter.git](git@github.com:line/line-login-starter.git)

```
$ git clone git@github.com:line/line-login-starter.git
```

2. Log in to Heroku using Heroku CLI. Heroku credentials are required.

```
$ heroku login
```

3. Add remote to local repository

```
$ heroku git:remote -a name-of-heroku-app
```

4. Push code to Heroku remote. Note: Heroku only deploys code that is pushed to the `master` branch.

```
$ git push heroku master
```

<!--
### How to view logs 

- Log in to Heroku using Heroku CLI

```
$ heroku login
```

- Clone the app

```
$ heroku git:clone -a name-of-heroku-app
```

- Check logs

```
$ heroku logs --tail -a name-of-heroku-app
```

-->


