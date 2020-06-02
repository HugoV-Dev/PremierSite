# PremierSite

Pour lancer le conteneur sur le mac :
docker run -v /Users/hugovinson/Documents/PremierSite:/var/www/html -v -d --name webserver -p 80:80 -p 3306:3306 --restart=always lioshi/lamp:php5
