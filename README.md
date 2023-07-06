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
```