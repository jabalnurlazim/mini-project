# mini-project

**Endpoints:**<br/>
1.  url: http://localhost:8080/createUser<br/>
    request method: POST<br/>
    description: create single user per transaction<br/>
    sample input: <br/>
   ```json
   {
      "username": "jlazim2212",
      "fullname": "jabalnur Lazim",
      "birthday": "02-05-1991",
      "gender": "male"
    }
  ```
2.  url: http://localhost:8080/createUsers<br/>
    request method: POST<br/>
    description: create multiple users per transaction<br/>
    sample input: <br/>
   ```json
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
```
3. url: http://localhost:8080/getUser/jlazim<br/>
   request method: GET<br/>
   description: retrieve single user per transaction<br/>
   
4. url: http://localhost:8080/getUsers<br/>
   request method: GET<br/>
   description: retrieve all users (active) per transaction<br/>

**Notes:** <br/>
1. Please add single header<br/>
    - header name: `Authorization`<br/>
    - header value: `j32io33ise4k2qq1`<br/>

2. Execute SQL statement located at (/src/main/resources/db)<br/>
    
