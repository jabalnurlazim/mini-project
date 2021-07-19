# mini-project

Endpoints:
1.url: http://localhost:8080/createUser<br/>
  request method: POST
  description: create single user per transaction
  sample input: 
    {
      "username": "jlazim2212",
      "fullname": "jabalnur Lazim",
      "birthday": "02-05-1991",
      "gender": "male"
    }

2.url: http://localhost:8080/createUsers
  request method: POST
  description: create multiple users per transaction
  sample input: 
    {
      "users": [
        {
          "username": "jlazim222",
          "fullname": "jabalnur Lazim",
          "birthday": "02-05-1991",
          "gender": "male"
        },
        {
          "username": "jlazim112",
          "fullname": "jabalnur Lazim",
          "birthday": "02-05-1992",
          "gender": "male"
        }
      ]
    }

3. url: http://localhost:8080/getUser/jlazim
   request method: GET
   description: retrieve single user per transaction
   
4. url: http://localhost:8080/getUsers
   request method: GET
   description: retrieve all users (active) per transaction

Notes: 
1. Please add single header
    - header name: Authorization
    - header value: j32io33ise4k2qq1

2. Execute SQL statement located at (/src/main/resources/db)
    
