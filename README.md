# web server for local development 
### Setup:
```
npm install
```

### Run web server: app listens port 3000
```
npm run dev
```

### Test web server with Postman: 
* send request to 
```
http://localhost:3000/login
```
* request body is
```
{
  "email": "test@gmail.com",
  "password": "123456"
}
```
* example answer is:
```
{
    "accessToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjoidXNlciBuYW1lIiwiYWRtaW4iOnRydWUsImlhdCI6MTY4MDQxNjQ1NSwiZXhwIjoxNjgwODQ4NDU1fQ.y8fRB3pBQrnZPxndrU6irnqY5ijbPSMrORYY3BP5I3E"
}
```