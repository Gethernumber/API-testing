# 🚀 Комплексное тестирование API (REST & SOAP)

В данном разделе представлены примеры тестирования двух типов архитектур API с использованием **Postman**:

### 1. REST API (Проект DemoShopping)

- **Стек:** JSON, методы GET/POST/PUT/PATCH/DELETE.
- **Что сделано:** Проверены основные бизнес-сценарии (авторизация, работа с корзиной). Написаны автотесты на JavaScript для валидации статус-кодов и структуры JSON-ответов.

### 2. SOAP API (Сервис CountryInfo)

- **Источник:** [CountryInfoService WSDL](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL)
- **Стек:** XML, работа с конвертами (Envelopes), заголовок `Content-Type: text/xml`.
- **Что сделано:** Реализованы запросы для получения информации о странах. Настроен парсинг XML-ответов и проверка корректности данных через скрипты Postman.
