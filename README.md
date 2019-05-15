# Project Name: Linux Server Configuration.
This project sets up a linux server to serve a previously prepared web application.

#### Software installed
- Python 3
- Flask
- SQLAlchemy
- Oauth2client
- Httplib2
- PostgreSQL
- mod_wsgi

#### Configuration changes
- SSH port changed from 22 to 2200
- HTTP port changed to 80
- NTP port changed to 123
- Created user grader and gave it sudo rights
- Disabled root login
- Changed local timezone to UTC
- Installed git
- Pulled web app
- Created catalog user on PostgreSQL
- Made changes to web app code to create database with catalog user
- Created conf files necessary for apache to server the application

#### Third party resource
- Repo: https://github.com/EricM321/udacity-catalog-web-app
- PostgreSQL database user needed to be set up and changes in urls also needed to be made

#### Website address
- http://34.243.191.209.nip.io/

#### Connecting to the server
```
$ ssh -i <grader private key name>.pem grader@34.243.191.209 -p 2200
```
