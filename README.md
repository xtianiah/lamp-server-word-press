# lamp-server-word-press
#### lamp server
#### Created Ubuntu server on Virtualbox
#### I clone the new server and name it with a CLONE prefix
#### the system was updated using apt-get update
#### lamp server was installed using apt-get install lamp-server^
#### wordpress DATABASE Initialization - mysql -u root p
##### after initializing wordpress the below commands were initiated
#### CREATE DATABASE wordpressdb
#### CREATE USER wordpressgbemmy@localhost IDENTIFIED BY 'wordpresspassword'
#### GRANT ALL PRIVILEGES ON wordpressdb.* TO wordpressgbemmy@localhost
#### FLUSH PRIVILEGES
#### EXIT
#### WORDPRESS was then installed using cd /tmp
#### wget http://wordpress.org/latest.zip, i used ls to verify the download
#### the download was then unzip using unzip -q latest.zip -d /var/www/html/
#### chown -R www-data:www-data /var/www/html/wordpress
#### chmod -R 755 /var/www/html/wordpress
#### mkdir -p /var/www/html/wordpress/wp-content/uploads
#### chown -R www-data:www-data /var/www/html/wordpress/wp-content/uploads
#### I used ifconfig to check the ipaddress,copy and paste it in webbrowser to create wordpress
#### Wordpress was successfully configured.   



