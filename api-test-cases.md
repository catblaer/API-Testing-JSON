# Тест-кейсы для API (REST)

### TC-API-001: Получение полного списка постов (GET)
- **Метод:** GET
- **URL:** `https://jsonplaceholder.typicode.com/posts`
- **Ожидаемый результат:** Статус-код `200 OK`. Тело ответа — массив JSON, содержащий 100 объектов.
- **Фактический результат:** Статус-код `200 OK`. Получен массив из 100 элементов со структурой: `userId`, `id`, `title`, `body`.
- **Статус:** Пройден (Passed)

### TC-API-002: Создание нового поста (POST)
- **Метод:** POST
- **URL:** `https://jsonplaceholder.typicode.com/posts`
- **Payload (JSON):**
