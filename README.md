📝 TaskFlow — Приложение для управления задачами (Java + Spring Boot + PostgreSQL)

![Java Spring boot - Вступление-Обложка](https://github.com/user-attachments/assets/c19db5e3-59a7-4ec2-9500-5664e13f1420)


📌 Описание проекта
TaskFlow — это полноценное веб-приложение для управления задачами, разработанное на основе Java 17, Spring Boot, PostgreSQL и Thymeleaf. Цель проекта — показать, как реализовать MVC-архитектуру, создать RESTful-функциональность и визуальный интерфейс для взаимодействия с задачами.

Проект подходит для:
начинающих разработчиков, изучающих Java и Spring Boot;
студентов, которым нужен практический пример веб-приложения;
преподавателей и блогеров, создающих обучающие курсы.

🚀 Функциональные возможности:
✅ Создание задач
✏️ Редактирование задач
🗑️ Удаление задач
📋 Просмотр всех задач
🔄 Изменение статуса задач (выполнено/не выполнено)
💻 Веб-интерфейс на Thymeleaf с формами и кнопками управления

⚙️ Стек технологий
Java 17
Spring Boot 3.x
Spring Data JPA
PostgreSQL
Thymeleaf
Lombok
Bootstrap 5

📦 Установка и запуск
Клонируйте репозиторий:

git clone https://github.com/your-username/taskflow.git
cd taskflow
Создайте базу данных PostgreSQL:


CREATE DATABASE taskflow_db;
Настройте application.properties:


spring.datasource.url=jdbc:postgresql://localhost:5432/taskflow_db
spring.datasource.username=ваш_логин
spring.datasource.password=ваш_пароль
spring.jpa.hibernate.ddl-auto=update
Запустите проект:


./mvnw spring-boot:run
Откройте в браузере:

arduino
Копировать
Редактировать
http://localhost:8080
📂 Структура проекта
bash
Копировать
Редактировать
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
📚 Домашние задания (если используется в курсе)
🛠️ Реализовать возможность фильтрации задач по статусу

📆 Добавить дату создания задачи

🔔 Реализовать напоминания или сортировку задач

🤝 Благодарности
Проект создан в рамках обучающего курса на YouTube.
Поддержите проект звездой ⭐ и подпиской на канал!

👉 YouTube курс
👉 GitHub автора
