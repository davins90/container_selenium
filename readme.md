# Info

The goal of this image is to create a Jupyter environment useful to perform analysis related to the world of data science and (eventually) build browser automation tool with Selenium

Repo containing files useful to launch a docker image with two containers inside. These are:
- container 1: jupyter lab based on data science e python 3.9.2 images --> porta:8080
- container 2: run selenium --> porta:4444 --> the passwrod for entering into the VNC is "secret"

# Comandi
- docker-compose build = builds the image for the first time by installing the libraries. Use it on every first launch.
- docker-compose up = turn on the image.
- docker-compose down = turn off the image.

Aggiornamento: 6/5/22