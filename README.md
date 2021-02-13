# docker-laravel620-cluster
docker-laravel620-cluster

# main file config nginx

nano conf.d/default.conf

cp html/.env.example html/.env

nano html/.env

APP_URL=http://192.168.4.42:7000

php artisan key:generate

# permission

sudo chmod -R 755 html/

sudo chmod -R o+w html/storage

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


## modby => wachira90@yahoo.com
