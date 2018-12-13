## Отчет по лабораторным работам
## Выполнил студент группы ИДБ-15-13  Прокофьев Кирилл
<details> 
<summary>Нажмите сюда для раскрытия Лабораторных работ 1 - 3 </summary>
  
### Лабораторная работа 1.
Создание IDEF0-диаграммы "Производство оборудования" в RAMUS (программное средство разработки структурно-функциональных моделей)
* IDEF0-диаграмма в развернутом виде
![](https://github.com/really562/prokofev.github.io/blob/master/6%20вопросов%20(задание).png)

* [IDEF0-диаграмма в формате .rsf](https://github.com/really562/prokofev.github.io/blob/master/6%20вопросов%20(задание).rsf)

Создание диаграммы классов и диаграммы прецедентов в PLANTUML (программное средство автоматической генерации UML-диаграмм)
* [Текст](https://github.com/really562/prokofev.github.io/blob/master/UML%20(Диаграмма%20классов%20ЗАДАНИЕ)) и рисунoк диаграммы классов

![](https://github.com/really562/prokofev.github.io/blob/master/Диаграмма%20классов%20(задание).png)

* [Текст](https://github.com/really562/prokofev.github.io/blob/master/UML%20(Диаграмма%20прецедентов%20ЗАДАНИЕ)) и рисунок диаграммы прецедентов

![](https://github.com/really562/prokofev.github.io/blob/master/Диаграмма%20прецедентов%20(задание).png)

***

### Лабораторная работа 2-3.
* IDEF0

![](https://github.com/really562/prokofev.github.io/blob/master/Лаба%202_1.png)

* Plan-Do-Check

![](https://github.com/really562/prokofev.github.io/blob/master/Лаба%202_2.png)

* DFD

![](https://github.com/really562/prokofev.github.io/blob/master/Лаба%202_3.png)

* [Диаграмма в формате .rsf](https://github.com/really562/prokofev.github.io/blob/master/Лаба2.rsf)

***
</details>

## Лабораторная работа 4 (Курсовой проект)

### Выполнено на основании ВКР "Разработка автоматизированной системы деятельности агентства в сфере туризма"
### Определение основных средств автоматизации
Определение требований к модели
* Формальное определение объекта моделирования (процесса) - Автоматизация процесса бронирования туров
* Формальное определение точки зрения (владелец, руководитель) - Директор туристического агентства
* Формальное определение цели моделирования (вопросы к модели) - выделение процессов, требующих улучшения путем автоматизации.
* Формальное определение темы курсового проекта (наименование информационной системы) - Проектирование информационной системы для бронирования туров

[Файл RAMUS](https://github.com/really562/prokofev.github.io/blob/master/Курсовой%20проект.rsf)

### Определение основных средств автоматизации
* Определение конфигурации технических средств (рабочие станции, серверы, другое оборудование): ПК используемые клиентами, сервер на котором будут хранится базы данных, ПК сотрудников на которых установлена система бронирования.
* Определение конфигурации программных средств: Система будет разрабатываться в среде разработки Atom с использование языка html\php\mysql, а также  Android Studio с использованием языка Java
* Определение допустимых видов хранилищ и их размещения: скрины хранилищ

![](https://github.com/really562/prokofev.github.io/blob/master/11.png)

### Завершение идентификации всех потоков

* Построение ERD (диаграммы классов без атрибутов) для всех потоков. 

![](https://github.com/really562/prokofev.github.io/blob/master/streams.png)

[Код PlantUML](https://github.com/really562/prokofev.github.io/blob/master/streams.txt)

### Завершение идентификации всех ролей.

* Построение ERD (диаграммы классов без атрибутов) для всех ролей.

![](https://github.com/really562/prokofev.github.io/blob/master/uml.png)

[Код PlantUML](https://github.com/really562/prokofev.github.io/blob/master/umlr.txt)

### Завершение идентификации всех модулей.

* Построение ERD (диаграммы классов без атрибутов) для всех модулей.

![](https://github.com/really562/prokofev.github.io/blob/master/modules.png)

[Код PlantUML](https://github.com/really562/prokofev.github.io/blob/master/modules.txt)

### Разработка диаграммы РАМУС

* Контекстная диаграмма А0 - "Бронирование туров"

![](https://github.com/really562/prokofev.github.io/blob/master/course/01_A0.png)

* Декомпозиция диаграммы уровня A0 (A1-A3) на три блока

![](https://github.com/really562/prokofev.github.io/blob/master/course/02_A0.png)

* Декомпозиция блока А3 (A31-A33) - "Оформление документов" на три блока

![](https://github.com/really562/prokofev.github.io/blob/master/course/04_A3.png)

* Декомпозиция блока А33 (A331-A334) - "Передача документов" на четыре блока

![](https://github.com/really562/prokofev.github.io/blob/master/course/07_A33.png)
***

## Лабораторная работа 5 (Курсовой проект)

### Разработка диаграмм в RAMUS - декомпозиция всех автоматизируемых блоков в DFD

* Декомпозиция блока А1 - "Выбрать туры"

![](https://github.com/really562/prokofev.github.io/blob/master/course/03_A1.png)

* Декомпозиция блока А31 - "Оформить договор"

![](https://github.com/really562/prokofev.github.io/blob/master/course/05_A31.png)

* Декомпозиция блока А32 - "Оплата"

![](https://github.com/really562/prokofev.github.io/blob/master/course/06_A32.png)

***
