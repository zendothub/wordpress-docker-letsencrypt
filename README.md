# wordpress-docker-letsencrypt
This repo hosts file structure for hosting  wordpress using docker and letsencrypt with ssl encryption support.

### This is a public repository
It can be used to create wordpress on any virtual machine/ server like AWS EC2 instance. Simply pull the repository and do the following.
### Steps to create this server
- Simply update your domain name in `apache-custom.conf`
- make a copy of `.env.sample` to `.env`
- Fill all the values in `.env`
- Make sure your domain is pointing ti this instance , otherwise ssl certificate will not be wwww
- Run `docker-compose up -d` to start the server
- Create two folder here: `wp-data` and `letsencrypt`
- Now it will be accessible from your domain
  
