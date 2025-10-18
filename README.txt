mongodb://13.222.182.123:27017/

13.222.182.123:27017

npm install

npm run prod

####

{
  "text": "fff",
  "createdAt": { "$date": "2025-08-12T12:52:21.546Z" },
  "updatedAt": { "$date": "2025-08-12T12:52:21.546Z" },
  "__v": { "$numberInt": "0" }
}


###########
## BACKEND:

.env.prod
PORT=5000
MONGO_URI=mongodb://mongo:27017/todo
JWT_SECRET=your_secret_code

##
git status && git add . && git status && git commit -m "&& commit" && git push

## ##

place need to change ip:

1: in repo 

.env.prod frontend:

VITE_API_URL=http://34.229.222.21:5000/api

2: local compose changes 

mongodb compose local db connection:

and create database like:
todo

and collection name like : tasks

table like in Insert Document

{
  "text": "fff",
  "createdAt": { "$date": "2025-08-12T12:52:21.546Z" },
  "updatedAt": { "$date": "2025-08-12T12:52:21.546Z" },
  "__v": { "$numberInt": "0" }
}

3: ec2 instance changes. required

login ec2 and chage ip 

file: 
.env.prod 
folder:
frontend:

VITE_API_URL=http://34.229.222.21:5000/api

##
vi frontend/.env.prod

