# Документация API

## Обзор
API для управления аккаунтами, объявлениями и комментариями.  
Поддерживает регистрацию, аутентификацию, работу с объявлениями и комментариями.

## Базовый URL
`http://localhost:8080`

## Конфигурация
Основные настройки приложения находятся в файле `application.properties`.  
Пример конфигурации:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/your_db
spring.datasource.username=your_username
spring.datasource.password=your_password