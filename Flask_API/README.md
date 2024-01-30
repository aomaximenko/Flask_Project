## запуск приложения

```
flask --app Flask_API/server.py run
```

## тестирование с помощью Postman

### добавление нового события
- пример запроса: 2023-01-01|meet|onboarding
- HTTP метод: POST
- URL: http://127.0.0.1:5000/api/v1/calendar

### получение всего списка событий
- HTTP метод: GET
- URL: http://127.0.0.1:5000/api/v1/calendar

### получение события по идентификатору / ID == 1
- HTTP метод: GET
- URL: http://127.0.0.1:5000/api/v1/calendar/1

### обновление текста события по идентификатору / ID == 1
- пример запроса: 2023-01-01|meet|kick-off
- HTTP метод: PUT
- URL: http://127.0.0.1:5000/api/v1/calendar/1

### удаление события по идентификатору / ID == 1
- HTTP метод: DELETE
- URL: http://127.0.0.1:5000/api/v1/calendar/1