# Python/Django Quickstart with Codeship Pro
[ ![Codeship Status for whiteotter/python-django-quickstart](https://app.codeship.com/projects/bcb61790-b925-0135-c668-5e6c0be4bac8/status?branch=master)](https://app.codeship.com/projects/259132)

A [Todo Backend](http://todobackend.com/) community project configured for testing on [Codeship Pro](https://codeship.com/features/pro)

## Local Setup
- Boot up app on local machine with [Docker Compose](https://docs.docker.com/compose/gettingstarted/) -- `docker-compose up`
- Run a Codeship Pro build on your local machine with our [CLI tool](https://documentation.codeship.com/pro/builds-and-configuration/cli/) -- `jet steps`

## SCM Setup
- Initialize as a new git repo -- `rm -rf .git && git init && git add . && git commit -m 'first commit'`
- Create new repository on your SCM of choice (Github, Gitlab, Bitbucket) and push commit

## CI/CD Setup
- Sign up for a [free Codeship Pro account](https://codeship.com/features/pro)
- Once signed in, follow prompts to set up a Codeship Pro project
- Commit a change to your repo and watch as a Codeship Pro build is triggered!