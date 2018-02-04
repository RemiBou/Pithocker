# Pithocker
Personnal project. Trying to learn python, django, and the docker ecosystem.
# Steps followed
- Install python "choco install python"
- Install docker windows toolbox (because I'm using Windows Home) "choco install docker-toolbox -ia /COMPONENTS="kitematic,virtualbox,dockercompose" "
- run the docker toolbox terminal (on the first run it might take a while to init everything)
- build the docker image : cd on the project folder then "docker build . -t pythocker"
- run the image : "docker run -p 8000:8000 -it pythocker"