# краткая инструкция по запуску задания


## в инструкции указаны примеры тела запросов, HTTP метод и соответствующие URL для осуществления операций

1. Создать пользователя: curl -X POST -H "Content-Type: application/json"
-d '{"username":"Mashenka","email":"mashenka3@something.com"}' http://localhost:5000/users

2. Получение списка всех пользователей: curl http://localhost:5000/users

3. Получение пользователей по ID: curl http://localhost:5000/users/1

4. Удаление пользователя по ID: curl -X DELETE http://localhost:5000/users/1

5. Создание постов: curl -X POST -H "Content-Type: application/json"
-d '{"title":"First Post","content":"Hello, world!","author_id":1}' http://localhost:5000/posts

6. Получение списка постов: curl http://localhost:5000/posts

7. Получение поста по ID: curl http://localhost:5000/posts/1

8. Удаление поста по ID: curl -X DELETE http://localhost:5000/posts/1

    -- Проверено на Postman



