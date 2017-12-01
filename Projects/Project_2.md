# ITDC-JAVA
Проект №2
=========

## Организация работ

Для этой работы вам нужно продолжать использовать систему контроля версий _Git_.
Создайте новый репозиторий для хранения исходного кода вашего проекта под названием
_Map_.

Репозиторий должен содержать исходные файлы и все сопроводительные документы
проекта. Репозиторий НЕ должен содержать производные (генерируемые) файлы
(например, скомпилированные .class файлы программы).

## Ключевые инструменты разработчика Java

* [Java Development Kit](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* [Eclipse IDE](https://eclipse.org/downloads/packages/eclipse-ide-java-developers/oxygenr)

### Альтернативная среда разработки (по желанию)

* [IntelliJ IDEA](https://www.jetbrains.com/idea)

## Схема здания

В этом проекте вам необходимо написать приложение для просмотра, создания и
редактирования схем зданий на языке Java. В этой работе данные приложения должны
храниться в реляционной базе данных MySQL. Приложение должно иметь графический
пользовательский интерфейс. Для решения используйте управляющие конструкции,
циклы, и массивы. Используя объектно-ориентированный подход, разбейте ваше решение
на набор связанных объектов. Объекты задайте созданием их схем в классах. Для
реализации графического интерфейса используйте существующие классы из библиотеки
Java Swing.

### Пользовательские истории

Ниже приведено письмо рассказа заказчика. Ваша задача составить список
требований на основе этой истории. Требования нужно оформить как официальный
документ технического задания проекта.

_"Здравствуйте,_

_Я бы хотел заказать следующий программный продукт исходя из моей ситуации._

_Наш университет закончил строительство нового здания. Здание имеет 5 этажей.
Каждый этаж имеет около 50-ти помещений. Помещения включают в себя аудитории для
занятий и различные офисы администрации. При переезде из старого здания, мы,
как администрация, считаем, что у людей первое время будет много проблем найти
нужные кабинеты и офисы. Кроме того, каждый год к нам поступает около 500 новых
студентов, которые имеют проблемы в адаптации найти нужное помещение
на этапах регистрации. Мы хотели бы иметь простую информационную систему для показа
интерактивных схем этажей на пользовательских терминалах здания и компьютерах
лабораторий. Карта каждого этажа должна включать графическую схему помещений с
номерами офисов. Графическое представление должно быть схематично представлено в 2-D
или 3-D виде. По нажатию на помещение необходимо иметь возможность получить информацию
о кабинете. Каждый этаж можно выбрать при помощи меню, списка или выпадающего списка.
Программа должна позволять производить текстовый поиск по всей информации
и выделять нужный кабинет при нахождении результата. Для создания и редактирования
схемы здания, администрация должна использовать другое приложение. В этом приложение, кроме
просмотра, можно производить операции создания, редактирования и удаления кабинетов.
Создание должно производиться интерактивно рисованием графических
примитивов вроде прямоугольников и окружностей в 2-D или параллелепипедов и
цилиндров в 3-D. Изменение положения тоже должно производиться интерактивно
перемещением объекта на поле. Для каждого выбранного объекта можно редактировать
текстовые поля с названием кабинета и описанием помещения. Вся информация должна
храниться в базе данных на отдельном сервере организации. Схема данных должна быть
простой, дабы можно было использовать эту базу в других приложениях университета._

_С уважением,
Джон Доу"_

Каждое требование должно быть разбито на набор заданий. Изменения кода для
выполнения каждого задания рекомендуются сохранять как отдельные слепки в
системе контроля версий.

Задания можно хранить вместе с репозиторием сервиса **GitHub** (закладка
_Issues_), и визуально представлять рабочий процесс на _Kanban_-подобной доске
(закладка _Projects_).

![Project](https://i.imgur.com/ysVAyop.png)

### Оценивание работы

Работа будет оценена от 0 до 100 баллов исходя из следующих рубрик

* Верное формирование минимальных требований с рассказа заказчика: 15 баллов
* Наличие сопроводительных документов (технического задания, документации): 5 баллов
* Выполнение всех минимальных требований: 30 баллов
* Эффективность готового решения (с точки зрения производительности): 5 баллов
* Надежность готового решения (проведение тестирования продукта): 10 баллов
* Своевременная сдача проекта: -10 баллов за каждый просроченный день
* Логичное разбиение решения на объекты и методы, продуманная схема данных: 20 баллов
* Обоснованное использование элементов языка разработки: 10 баллов
* Высокое стилевое качество кода: 5 баллов

### Сдача работы

На всю работу вам предоставляется три недели. Финальный и промежуточные варианты
должны быть загружены в ваш публичный репозиторий на сервисе GitHub. Ссылка на
репозиторий должна быть передана преподавателю на почту для проверки.

### Чтение

### Чтение

* Java 8. Полное руководство, Девятое издание, Герберт Шилдт: Глава 8, 9, 10, 31, 32
* Java 8. Руководство для начинающих, Шестое издание, Герберт Шилдт: Глава 7, 8, 9, 16
* По желанию: Introduction to Java Programming. Comprehensive, Десятое издание, Y. Daniel Liang: Глава 11, 12, 13, 14, 15, 16, 17

### Документация

* [Java Graphics2D API](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)

* [ProGit](https://git-scm.com/book/ru/v2)