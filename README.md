####################  EXAMPLE_01  ####################

docker build -t luisaybar/mynginx:1.0 .

docker run -d -p 90:90 luisaybar/mynginx:1.0

http://localhost

docker ps

docker stop [imagen_id]

####################  DOCKER HUB  ####################

docker login

docker push luisaybar/mynginx:1.0

docker run -d -p 90:90 luisaybar/mynginx:1.0

http://localhost

docker ps

docker stop [imagen_id]

#########################################################
#########################################################

####################  EXAMPLE_02  ####################

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



#########################################################
#########################################################

####################  EXAMPLE_03  ####################

docker build -t luisaybar/my_ml_model_v2:1.0 .

docker run -d -p 100:100 luisaybar/my_ml_model_v2:1.0

docker ps

docker stop [imagen_id]

####################  DOCKER HUB  ####################

docker login

docker push luisaybar/my_ml_model_v2:1.0

docker run -d -p 100:100 luisaybar/my_ml_model_v2:1.0

http://localhost

docker ps

docker stop [imagen_id]
