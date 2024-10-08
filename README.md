# Real Estate Broker
Full Stack Web Application developed using **React, Django & MySQL**. Course Project for CS253 - Software Development and Operations

## Build

```
git clone https://github.com/utpaldwivedi/Real-Estate-Broker-WebApp.git
```

### Client 
```
cd Client
npm install
npm run dev
```

### Server

1. Package Installations
```
pip install django
pip install mysqlclient
```

2. Database Setup
    * Install MySQL
    * Create database/schema named *real_estate_broker*
    * Create user named *dev* with password *123* with DBA role (full access to the above database)

3. Run Server
```
cd server
python manage.py makemigrations
python manage.py migrate 
python manage.py runserver [port]
```

## Tech Stack

### Frontend
ReactJS

### Backend
Django

### Database
MySQL
