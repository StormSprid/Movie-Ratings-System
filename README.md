# 🎬 Movie Ratings System

## ✨ Описание
"Movie Ratings System" — это простое веб-приложение на Java/Spring Boot, позволяющее пользователям оценивать фильмы и смотреть средние рейтинги.

## 🔧 Технологии
- Java 17+
- Spring Boot
- Spring Data JPA
- Spring Security (JWT или Basic Auth)
- PostgreSQL
- Lombok
- Docker (Optional)
- MapStruct (Optional)
- Swagger (Optional)

## 📅 Функционал
- 🔑 Регистрация и логин пользователей
- 🎥 Список фильмов (CRUD)
- ⭐ Добавление оценок к фильмам (1-10)
- 🔢 Вывод среднего рейтинга для каждого фильма
- 🔍 Поиск фильмов по названию и жанру
- ⏳ Сортировка по рейтингу

## 🔖 Структура проекта
```bash
src/main/java/com/example/movieratingsystem/
├── controller/
├── dto/
├── entity/
├── repository/
├── service/
├── security/
```

## 🚀 Запуск проекта
```bash
# Собрать проект
./mvnw clean install

# Запустить приложение
./mvnw spring-boot:run
```

## 🔍 Swagger UI (API документация)
После запуска доступен по адресу:
```
http://localhost:8080/swagger-ui.html
```

## 🔗 То-до (что ещё можно добавить)
- Лайки/дизлайки к комментариям
- Рекомендации по фильмам
- Админ-панель для управления фильмами и пользователями

---
Проект поможет укрепить навыки Java и Spring Boot и будет отлично выглядеть на GitHub! 🚀

