# Kudo

A simple CRUD App with Python, Flask, and React

## Running the Application

### Start MongoDB Service

```
set MONGO_URL=mongodb://mongo_user:mongo_secret@0.0.0.0:27017/
docker-compose up
```

### Start Flask Service

```
set FLASK_APP=./app/http/api/endpoints.py
set FLASK_ENV=development
pipenv run python -m flask run --port 4433
```

### Start React Service

```
cd ./app/http/web/app
npm start
```
