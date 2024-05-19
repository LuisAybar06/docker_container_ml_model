####################  TEST  ####################

docker build -t luisaybar/mynginx:1.0 .

docker run -d -p 80:80 luisaybar/mynginx:1.0

http://localhost

docker ps

docker stop [imagen_id]

####################  DOCKER HUB  ####################

docker login

docker push luisaybar/mynginx:1.0

docker run -d -p 80:80 luisaybar/mynginx:1.0

http://localhost

docker ps

docker stop [imagen_id]

#########################################################
#########################################################

####################  FASTAPI / ML MODEL  ####################

docker build -t luisaybar/my_ml_model:1.0 .

docker run -d -p 80:80 luisaybar/my_ml_model:1.0

docker ps

docker stop [imagen_id]

####################  DOCKER HUB  ####################

docker login

docker push luisaybar/my_ml_model:1.0

docker run -d -p 80:80 luisaybar/my_ml_model:1.0

http://localhost

docker ps

docker stop [imagen_id]
