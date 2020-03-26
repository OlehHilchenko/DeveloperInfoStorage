Теория:

https://proselyte.net/tutorials/jdbc/
https://habr.com/sandbox/112346/
https://proselyte.net/tutorials/maven/
https://proselyte.net/tutorials/junit/
https://www.baeldung.com/mockito-series

Практика:

Необходимо реализовать консольное CRUD приложение, которое взаимодействует с БД и позволяет выполнять все CRUD операции над сущностями:
Skill (id, name)
Specialty (id, name, description)
Developer(id, firstName, lastName, Specialty specialty, List<Skill> skills)
Требования:

Придерживаться шаблона MVC (пакеты model, repository, service, controller, view)
Для миграции БД использовать https://www.liquibase.org/
Сервисный слой приложения должен быть покрыт юнит тестами (junit + mockito).
Для импорта библиотек использовать Maven
Результатом выполнения проекта должен быть отдельный репозиторий на github, с описанием задачи, проекта и инструкцией по локальному запуску проекта.

Технологии: Java, MySQL, JDBC, Maven, Liquibase, JUnit, Mockito


