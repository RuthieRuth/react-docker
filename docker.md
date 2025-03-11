set up react
update vite
make a docker file outside src folder

in the vs code terminal:
run docker in the folder
docker ps -a
updated dockerfile. Apparently some operations are not needed 
and made the docker-compose.yaml file.
docker-compose up --build

result: one image in the react app is not working.
trying again:
- included volumes in my yml file, and built again
result: still the same problem

