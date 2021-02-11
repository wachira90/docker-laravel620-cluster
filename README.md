# docker-laravel620-cluster
docker-laravel620-cluster

# main file config 

nano conf.d/default.conf

# permission

cd html/

sudo chmod -R 0777 storage/

# for persistent connection php session

hash $remote_addr consistent; 

# run 
  docker-compose up -d

# stop 
  docker-compose stop 

# restart
  docker-compose restart

# shutdown
  docker-compose down

# URL
http://localhost:7000

http://localhost:7000/user

# modby => wachira90@yahoo.com

# docker-laravel620-cluster
