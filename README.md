ngphfpmypg.py script will wait input for IP, username, password and sitename. Script will install nginx web server to this server. After script will add virtualhost for sitename input. Then will print nginx web server is ready and if you want to install configure MySQL or PostgreSQL with php-fpm select from menu. Otherwise just press "Enter" button to exit. If you will choose "1", MySQL and PHP-FPM with extensions will be installed and configured(MySQL root password is: freebsd). Then script will ask about database, username and password for new virtualhost. If you will choose "2", PostgreSQL and PHP-FPM with extensions will be installed and configured. At the end script will create db user and pass for this virtualhost. If you will open page with http://virtualhostname you must see the installed MySQL version or for PostgreSQL one book submit page.

If you want to add new virtualhost just use add-vhost-ngphfpmypg.py.py script. Script will wait input for Nginx server IP, username, pass and for virtualhost name. After that script will check virtualhost name on the web server. If this name is exists on the Nginx web server, script will exit. If not exists, script will create all needs for this virtualhost.