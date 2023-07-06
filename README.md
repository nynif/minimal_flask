# Minimal flask server
This project is a minimal flask server, the purpose is just to test deployment on remote server.

1. Connect to your remote server
```
ssh root@ip_server
```

2. 
```
cd /var/www/
git clone https://github.com/nynif/minimal_flask.git
cp flask.conf /etc/apache2/sites-available/flask.conf
a2ensite flask.conf
systemctl restart apache2
```

a2dissite flask.conf

Check apache sytax 
apachectl -t


https://www.rosehosting.com/blog/how-to-install-flask-on-ubuntu-22-04-with-apache-and-wsgi/