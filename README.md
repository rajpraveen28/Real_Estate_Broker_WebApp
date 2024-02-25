Real Estate Broker Web Application developed for Neural Dynamics using React and Django

## Setup

```
git clone git@github.com:ChinmayPillai/Real_Estate_Broker_WebApp.git
```

### Client 
```
cd Client
npm install
npm run dev
```

### Server

1. Install Django and mysqlclient
```
pip install django
pip install mysqlclient
```

2. MySQL Setup
    * Install MySQL
    * Create database named *real_estate_broker*
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
1. ReactJS

### Backend
1. Django

### Database
MySQL
