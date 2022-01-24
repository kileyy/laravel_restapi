RESTAPI Employee 

GET METHOD: 

http://127.0.0.1:8000/api/employees

Find by ID:

http://127.0.0.1:8000/api/employee/1

POST request example:

curl -X POST -H “Content-Type: application/json”^
-d “{\”id\”:1000000003,\”name\”:\”Rose Soap\”,\”price\”:11.20,\”quantity\”:30}”^
http://localhost:8080/stocks


Latest Progress: (Error Code, Wait to fix) 

<!--
Illuminate\Database\QueryException: SQLSTATE[HY000]: General error: 1364 Field 'name' doesn't have a default value (SQL: insert into `employees` (`updated_at`, `created_at`) values (2022-01-24 10:14:32, 2022-01-24 10:14:32)) in file C:\Users\wenchin\Desktop\Laravel\example-app\vendor\laravel\framework\src\Illuminate\Database\Connection.php on line 712

#0 C:\Users\wenchin\Desktop\Laravel\example-app\vendor\laravel\framework\src\Illuminate\Database\Connection.php(672): Illuminate\Database\Connection-&gt;runQueryCallback('insert into `em...', Array, Object(Closure))
