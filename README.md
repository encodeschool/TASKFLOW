# 📝 TaskFlow — Приложение для управления задачами (Java + Spring Boot + PostgreSQL)

![Java Spring boot - Вступление-Обложка](https://github.com/user-attachments/assets/c19db5e3-59a7-4ec2-9500-5664e13f1420)


## 📌 Описание проекта
TaskFlow — это полноценное веб-приложение для управления задачами, разработанное на основе Java 17, Spring Boot, PostgreSQL и Thymeleaf. Цель проекта — показать, как реализовать MVC-архитектуру, создать RESTful-функциональность и визуальный интерфейс для взаимодействия с задачами.

Проект подходит для:<br />
начинающих разработчиков, изучающих Java и Spring Boot;<br />
студентов, которым нужен практический пример веб-приложения;<br />
преподавателей и блогеров, создающих обучающие курсы.<br />

## 🚀 Функциональные возможности:
✅ Создание задач<br />
✏️ Редактирование задач<br />
🗑️ Удаление задач<br />
📋 Просмотр всех задач<br />
🔄 Изменение статуса задач (выполнено/не выполнено)<br />
💻 Веб-интерфейс на Thymeleaf с формами и кнопками управления<br />

## ⚙️ Стек технологий
Java 17<br />
Spring Boot 3.x<br />
Spring Data JPA<br />
PostgreSQL<br />
Thymeleaf<br />
Lombok<br />
Bootstrap 5<br />

## 📦 Установка и запуск
1. Клонируйте репозиторий: 
```bash
git clone https://github.com/your-username/taskflow.git
cd taskflow
```

2. Создайте базу данных PostgreSQL:
```sql
CREATE DATABASE taskflow_db;
```

3. Настройте application.properties:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/taskflow_db
spring.datasource.username=ваш_логин
spring.datasource.password=ваш_пароль
spring.jpa.hibernate.ddl-auto=update
```

4. Запустите проект:

``` bash
./mvnw spring-boot:run
```

5. Откройте в браузере:
```arduino
http://localhost:8080
```


## 📂 Структура проекта
```bash
src/
 └── main/
     ├── java/com/example/taskflow/
     │   ├── controller/
     │   ├── service/
     │   ├── repository/
     │   ├── model/
     │   └── TaskFlowApplication.java
     └── resources/
         ├── templates/
         ├── static/
         └── application.properties
```

## 📚 Домашние задания (если используется в курсе)
🛠️ Реализовать возможность фильтрации задач по статусу<br />
📆 Добавить дату создания задачи<br />
🔔 Реализовать напоминания или сортировку задач<br />

## 🤝 Благодарности
Проект создан в рамках обучающего курса на YouTube.<br />
Поддержите проект звездой ⭐ и подпиской на канал!<br />

👉 <a href="https://www.youtube.com/watch?v=yoYwLXyD7nU&list=PL6slCWKROYnaSOd6sZLQtmqEGBKJP24eK">YouTube курс</a><br />
👉 <a href="https://github.com/encodeschool/TASKFLOW/tree/main">GitHub автора</a><br />
