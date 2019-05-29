# Dockerized Django Development

This material was presented to the Omaha Python User Group on 5/29/2019

## Abstract

Docker is a useful technology whose goal is to streamline software development and deployment.  

This presentation covers:

- The basics of DockerFiles;
- Using docker-compose for multi-container applications;
- How to set up a Django application as a custom Docker container and;
- Tips and tricks for developing with Docker and Django

This presentation has an accompanying code base which can be cloned from here:

https://github.com/Jeffallan/Ebook-API

## Viewing This Presentation Locally
- Clone this repository.
- Create a virtual environment and activate it:
```
python -m venv /path/to/ENV
source ENV/bin/activate
```
- Install the the requitred libraries in your virtual environment:
```
pip install -r requirements.txt
```
To open as a Jubyter Notebook:
```
jupyter notebook
```
To display as a slideshow:

```
jupyter nbconvert --to slides  --ServePostProcessor.port=8001 --ServerPostProcessor.ip='*' --post serve *.ipynb
```

## Good Resources To Learn More

- [Docker Installation Guide](https://docs.docker.com/install)
- [Docker Compose Installation Guide](https://docs.docker.com/compose/install/)
- [Taking Docker Container To Production](https://pythonspeed.com/articles/dockerizing-python-is-hard/)
- [Heroku.yml](https://devcenter.heroku.com/articles/build-docker-images-heroku-yml)
- [Deploying to Heroku](https://devcenter.heroku.com/articles/container-registry-and-runtime)
