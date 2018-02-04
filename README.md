# Pithocker
Personnal project. Trying to learn python, django, and the docker ecosystem (container, compose, prchestration) and maybe other nice technologies like hadoop or openfaas.
# Steps followed
- Install python "choco install python"
- Install docker windows toolbox (because I'm using Windows Home) "choco install docker-toolbox -ia /COMPONENTS="kitematic,virtualbox,dockercompose" "
- Install python django (installed in the container but I need it for initializing the project with django cli) : "pip install django"
- Init the project "django-admin startproject Pythocker" then cd to the project file
- Create the DockerFile
- run the docker toolbox terminal (on the first run it might take a while to init everything)
- build the docker image : cd on the project folder then "docker build . -t pythocker"
- run the image : "docker run -p 8000:8000 -it pythocker"

Here is my journey [https://twitter.com/rembou1/status/959536247155970049]