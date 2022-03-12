

[![Build status](https://ci.appveyor.com/api/projects/status/n9wefj6d3c8d3dkj?svg=true)](https://ci.appveyor.com/project/ZimovOleg/i)

## Домашнее задание к занятию «1.2. Тестирование API, CI»

- Настройка "Appveyor"
- Добавление JSON Schema
- Доработка JSON Schema (добавление способа валидации значения поля на два из возможных значения: "RUB" или "USD")

**Для запуска проекта:**
1. Склонировать проект из репозитория командой 

```
git clone https://github.com/ZimovOleg/-I.git
``` 
2. Открыть склонированный проект в Intellij IDEA
3. Открыть в терминале каталог ```artifacts```
4. Для запуска приложения ввести команду ```java -jar app-mbank.jar```
5. Запустить команду ```gradlew test```
6. Для просмотра результатов в Appveyor нажать на значок бейджика в README.md(в начале документа)
