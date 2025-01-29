# Домашнее задание к занятию «Введение в микросервисы»
## Задача
Руководство крупного интернет-магазина, у которого постоянно растёт пользовательская база и количество заказов, рассматривает возможность переделки своей внутренней ИТ-системы на основе микросервисов.

Вас пригласили в качестве консультанта для оценки целесообразности перехода на микросервисную архитектуру.

Опишите, какие выгоды может получить компания от перехода на микросервисную архитектуру и какие проблемы нужно решить в первую очередь.


## Ответ

Я бы предложил пеервести проект на микросервисную архитектуру выделив в отдельные сервисы БД и приложение интернет-магазина.
Это позволит гибче и эффективнее масштабировать сервис БД при дальнейшем росте, а также бесболезненного внедрять исправления и улучения приложения.
Кроме того это повысит отказоустойчивость всей системы, хоть и приведе к усложению в эксплуатации.
И необходимо обсепечить соответствующий уровень безопасности системы путем использования сертификатов или API Keys для каждого сервиса.
