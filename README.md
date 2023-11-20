# Разработка корпоративных информационных систем. Практическая работа 5
Варинат 6: Холодильник.


## Установка PostgreSQL:

   sudo apt-get update


   sudo apt-get install postgresql postgresql-contrib

## Инициализация бд:

   psql -U postgres -d postgres -f init.sql

   
## Инструкция по сборке и запуску
1. Сборка проекта: mvn pakage
2. Запуск из папки target: java -jar .\fourth-1.0-SNAPSHOT.jar
