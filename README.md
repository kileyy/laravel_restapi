RESTAPI Employee 

GET METHOD: 

http://127.0.0.1:8000/api/employees

Find by ID:

http://127.0.0.1:8000/api/employee/1

POST request example:

curl -X POST -H “Content-Type: application/json”^
-d “{\”id\”:1000000003,\”name\”:\”Rose Soap\”,\”price\”:11.20,\”quantity\”:30}”^
http://localhost:8080/stocks


