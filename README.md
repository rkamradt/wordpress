# WordPress

docker-compose.yml that will start up a WordPress instance for you. You will
need a ../config/wordpress.env file with the following:

WORDPRESS_DB_HOST=db
WORDPRESS_DB_USER=wpuser
WORDPRESS_DB_PASSWORD=<password>
WORDPRESS_DB_NAME=wpdb
MYSQL_DATABASE=wpdb
MYSQL_USER=wpuser
MYSQL_PASSWORD=<password>
MYSQL_RANDOM_ROOT_PASSWORD=1

You will also need a data and wordpress directory in the current directory, that
is where all the data will be stored.ß
