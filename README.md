# 🚀 Комплексное тестирование API (REST & SOAP)

В данном разделе представлены примеры тестирования двух типов архитектур API с использованием **Postman**:

### 1. REST API (Проект DemoShopping)

- **Стек:** JSON, методы GET/POST/PUT/PATCH/DELETE.
- **Что сделано:** Проверены основные бизнес-сценарии (авторизация, работа с корзиной). Написаны автотесты на JavaScript для валидации статус-кодов и структуры JSON-ответов.
- [Ссылка на Postman-коллекцию](https://www.postman.com/workspace/My-great-Team's-Workspace~f3ee829d-f25a-4aee-8704-7f0d02d0792c/collection/49502060-c443dd38-80d2-48aa-a59b-ba6ea3579e77?action=share&source=copy-link&creator=49502060)

### 2. SOAP API (Сервис CountryInfo)

- **Источник:** [CountryInfoService WSDL](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL)
- **Стек:** XML, работа с конвертами (Envelopes), заголовок `Content-Type: text/xml`.
- **Что сделано:** Реализованы запросы для получения информации о странах. Настроен парсинг XML-ответов и проверка корректности данных через скрипты Postman.
- [Ссылка на Postman-коллекцию](https://www.postman.com/workspace/My-great-Team's-Workspace~f3ee829d-f25a-4aee-8704-7f0d02d0792c/collection/49502060-a2191e11-1303-472c-9db5-352c72069282?action=share&source=copy-link&creator=49502060)
