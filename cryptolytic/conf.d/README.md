## These are the server configuration files for cryptolytic. (flask)
The port is socketed 8000 => 80 \
- NGINX/conf.d => /etc/nginx/conf.d/webaddress
- supervisor/conf.d => /etc/supervisor/conf.d/webaddress
**Unix command: gunicorn3 application:application**
### Deployed at:
http://45.56.119.8/