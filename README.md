# Яндекс Практикум / Аналитика данных / Реализация проектов

## Перечень проектов
| № п/п| Наименование проекта |
|:----:|----|
| 1 | [Исследование надёжности заёмщиков](#Исследование-надёжности-заёмщиков) |
| 2 | [Исследование объявлений о продаже квартир Санкт-Петербурга](#Исследование-объявлений-о-продаже-квартир-Санкт-Петербурга) |
| 3 | [Выявления прибыльного тарифа для телеком-компании](#Выявления-прибыльного-тарифа-для-телеком-компании) |
| 4 | [Сборный проект №1. Выявление закономерностей, определяющих успешность игры закономерностей](#Сборный-проект-1-Выявление-закономерностей-определяющих-успешность-игры-закономерностей) |
| 5 | [Анализ данных о фондах и инвестициях (SQL)](#Анализ-данных-о-фондах-и-инвестициях-SQL) |
| 6 | [Анализ доходности приложения Procrastinate Pro+](#Анализ-доходности-приложения-Procrastinate-Pro) |
| 7 | [Анализ базы данных пользователей StackOverflow (SQL)](#Анализ-базы-данных-пользователей-StackOverflow-SQL) |
| 8 | [Приоритезация гипотез по увеличению выручки интернет-магазина, оценка результатов А/B-тестов](#Приоритезация-гипотез-по-увеличению-выручки-интернет-магазина-оценка-результатов-АB-тестов) |
| 9 | [Изучение поведения пользователей мобильного приложения продуктов питания](#Изучение-поведения-пользователей-мобильного-приложения-продуктов-питания) |
| 10 | [Исследование рынка заведений общепита Москвы для принятия решения об открытии нового заведения](#Исследование-рынка-заведений-общепита-Москвы-для-принятия-решения-об-открытии-нового-заведения) |
| 11 | [Анализ пользовательского взаимодействия с карточками статей Яндекс.Дзен](#Анализ-пользовательского-взаимодействия-с-карточками-статей-ЯндексДзен) |
| 12 | [Выпускной проект. Выявление и анализ сегментов отточных клиентов банка](#Выпускной-проект-Выявление-и-анализ-сегментов-отточных-клиентов-банка) |

***
## ***Исследование надёжности заёмщиков***

**Файл проекта:** [#01_Project_Исследование_надежности заемщиков.ipynb](https://github.com/denzzers/semenoff_da23/blob/main/%2301_Project_Исследование_надежности%20заемщиков.ipynb)
|  | **Информация** | 
|:----:|----|
| **Описание проекта** | Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. |
| **Используемые библиотеки** | pandas, seaborn |
| **Приобритенные навыки** | <ul><li>Предобработка данных - пропуски, корректировка типов, дубликаты, выбросы, строковые аномалии, категоризация. </li><li>Анализ данных – зависимости, корреляции</li></ul> |
| **Проект на nbviewer.org** | [Посмотреть проект - Исследование надёжности заёмщиков](https://nbviewer.org/github/denzzers/semenoff_da23/blob/main/%2301_Project_Исследование_надежности%20заемщиков.ipynb) |

[:house:Перечень проектов](#Перечень-проектов)

## ***Исследование объявлений о продаже квартир Санкт-Петербурга***

**Файл проекта:** [#02_Project_Исследование объявлений о продаже квартир Санкт-Петербурга.ipynb](https://github.com/denzzers/semenoff_da23/blob/main/%2302_Project_Исследование%20объявлений%20о%20продаже%20квартир%20Санкт-Петербурга.ipynb)
|  | **Информация** | 
|:----:|----|
| **Описание проекта** | В вашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — провести исследовательский анализ данных, который поможет установить параметры, влияющие на цену объектов. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. |
| **Используемые библиотеки** | pandas, seaborn, matplotlib |
| **Приобритенные навыки** | <ul><li>Предобработка данных</li><li>Анализ данных</li><li>Инструменты построения графиков: hist(), boxplot(), plot()</li><li>Выборка срезов данных</li><li>Объединение таблиц посредством методов join() и merge()</li><li>Поиск и интерпритация взаимосвязи различных данных</li><li>Автоматизация процесса построения набора графиков</li></ul> |
| **Проект на nbviewer.org** | [Исследование объявлений о продаже квартир](https://nbviewer.org/github/denzzers/semenoff_da23/blob/main/%2302_Project_Исследование%20объявлений%20о%20продаже%20квартир%20Санкт-Петербурга.ipynb) |
| **Файл данных для проекта** | [Скачать файл - real_estate_data.csv](https://drive.google.com/file/d/16Y9Fj_4pI9YaJprGulWRNLAtBmdCzulw/view?usp=drive_link) |

[:house:Перечень проектов](#Перечень-проектов)

## ***Выявления прибыльного тарифа для телеком-компании***

**Файл проекта:** [#03_Project_Статический анализ данных_Определение лучшего тарифа оператора сотовой связи.ipynb](https://github.com/denzzers/semenoff_da23/blob/main/%2303_Project_Статический%20анализ%20данных_Определение%20лучшего%20тарифа%20оператора%20сотовой%20связи.ipynb)
|  | **Информация** | 
|:----:|----|
| **Описание проекта** | Необходимо сделать предварительный анализ тарифов "Ультра" и "Смарт" оператора сотовой связи "Мегалайн" на небольшой выборке клиентов, чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. |
| **Используемые библиотеки** | pandas, seaborn, matplotlib, numpy |
| **Приобритенные навыки** | <ul><li>Предобработка данных</li><li>Анализ данных</li><li>Построение гистограмм</li><li>Основы теории вероятности</li><li>Формирование статичесих гипотез, с последующей их проверкой</li></ul> |
| **Проект на nbviewer.org** | [Выявления прибыльного тарифа для телеком-компании](https://nbviewer.org/github/denzzers/semenoff_da23/blob/main/%2303_Project_Статический%20анализ%20данных_Определение%20лучшего%20тарифа%20оператора%20сотовой%20связи.ipynb) |
| **Файл данных для проекта** | <ul><li>[Скачать файл - users.csv](https://drive.google.com/file/d/1XBhd53Rsd9V6l-K3LPD7ryo9A1pa6eHU/view?usp=share_link)</li><li>[Скачать файл - calls.csv](https://drive.google.com/file/d/1wgA3_c5NyZQ6NPKVcm_OFbEd_e65pWWS/view?usp=share_link)</li><li>[Скачать файл - messages.csv](https://drive.google.com/file/d/1Ts7Z0HIzW9u95kyyihvHI0vbJiO3Bo9h/view?usp=share_link)</li><li>[Скачать файл - internet.csv](https://drive.google.com/file/d/1dF2TdxO-VX9kO8zOIR1JdXpVhPCI9EwJ/view?usp=share_link)</li><li>[Скачать файл - tariffs.csv](https://drive.google.com/file/d/1ZQEMMqiEJqE9c4XRukiHwwJvqW34cOuz/view?usp=share_link)</li></ul> |

[:house:Перечень проектов](#Перечень-проектов)

## ***Сборный проект №1. Выявление закономерностей, определяющих успешность игры закономерностей***

**Файл проекта:** [#04_Project_Выявление закономерностей_ определяющих успешность игры закономерностей.ipynb](https://github.com/denzzers/semenoff_da23/blob/main/%2304_Project_%D0%92%D1%8B%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B8%CC%86_%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D1%8F%D1%8E%D1%89%D0%B8%D1%85%20%D1%83%D1%81%D0%BF%D0%B5%D1%88%D0%BD%D0%BE%D1%81%D1%82%D1%8C%20%D0%B8%D0%B3%D1%80%D1%8B%20%D0%B7%D0%B0%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B8%CC%86.ipynb)
|  | **Информация** | 
|:----:|----|
| **Описание проекта** | Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.</br>Перед вами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.</br> |
| **Особенности проекта** | В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков». |
| **Используемые библиотеки** | pandas, seaborn, matplotlib, numpy |
| **Приобритенные навыки** | <ul><li>Предобработка данных</li><li>Анализ данных</li><li>Построение гистограмм</li><li>Формирование статичесих гипотез, с последующей их проверкой</li></ul> |
| **Проект на nbviewer.org** | [Сборный проект №1. Выявление закономерностей, определяющих успешность игры закономерностей](https://nbviewer.org/github/denzzers/semenoff_da23/blob/main/%2304_Project_%D0%92%D1%8B%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B8%CC%86_%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D1%8F%D1%8E%D1%89%D0%B8%D1%85%20%D1%83%D1%81%D0%BF%D0%B5%D1%88%D0%BD%D0%BE%D1%81%D1%82%D1%8C%20%D0%B8%D0%B3%D1%80%D1%8B%20%D0%B7%D0%B0%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B8%CC%86.ipynb) |
| **Файл данных для проекта** | [Скачать файл - games.csv](https://drive.google.com/file/d/1z8EVwrc7x4cX4lkZZs4yXcqnEpDK5NwO/view?usp=drive_link) |

[:house:Перечень проектов](#Перечень-проектов)

## ***Анализ данных о фондах и инвестициях (SQL)***

**Файл проекта:** [#05_Project_Анализ данных о фондах и инвестициях(SQL).txt](https://github.com/denzzers/semenoff_da23/blob/main/%2305_Project_%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%BE%20%D1%84%D0%BE%D0%BD%D0%B4%D0%B0%D1%85%20%D0%B8%20%D0%B8%D0%BD%D0%B2%D0%B5%D1%81%D1%82%D0%B8%D1%86%D0%B8%D1%8F%D1%85(SQL).txt)
|  | **Информация** | 
|:----:|----|
| **Описание проекта** | В самостоятельном проекте вам нужно проанализировать данные о фондах и инвестициях и написать запросы к базе. Задания будут постепенно усложняться, но всё необходимое для их выполнения: операторы, функции, методы работы с базой — вы уже изучили на курсе. К каждому заданию будет небольшая подсказка: она направит вас в нужную сторону, но подробного плана действий не предложит. |
| **Используемые инструменты** | Язык запросов SQL |
| **Приобритенные навыки** | <ul><li>Оператор WHERE</li><li>Операторы IN, LIKE, BETWEEN</li><li>Оператор GROUP BY</li><li>Оператор HAVING</li><li>ER-диаграммы</li><li>Оператор JOIN и его типы</li><li>Подзапросы в FROM и WHERE</li></ul> |
| **Проект на pastebin.com** | [Анализ данных о фондах и инвестициях (SQL)](https://pastebin.com/72mAm9L4) |
| **Файл данных для проекта** | [Скачать файл - games.csv](https://drive.google.com/file/d/1z8EVwrc7x4cX4lkZZs4yXcqnEpDK5NwO/view?usp=drive_link) |

[:house:Перечень проектов](#Перечень-проектов)

## ***Анализ доходности приложения Procrastinate Pro+***

[:house:Перечень проектов](#Перечень-проектов)

## ***Анализ базы данных пользователей StackOverflow (SQL)***

[:house:Перечень проектов](#Перечень-проектов)

## ***Приоритезация гипотез по увеличению выручки интернет-магазина, оценка результатов А/B-тестов***

[:house:Перечень проектов](#Перечень-проектов)

## ***Изучение поведения пользователей мобильного приложения продуктов питания***

[:house:Перечень проектов](#Перечень-проектов)

## ***Исследование рынка заведений общепита Москвы для принятия решения об открытии нового заведения***

[:house:Перечень проектов](#Перечень-проектов)

## ***Анализ пользовательского взаимодействия с карточками статей Яндекс.Дзен***

[:house:Перечень проектов](#Перечень-проектов)

## ***Выпускной проект. Выявление и анализ сегментов отточных клиентов банка***

[:house:Перечень проектов](#Перечень-проектов)
