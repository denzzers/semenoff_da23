# Яндекс Практикум / Аналитика данных / Реализация проектов

## Перечень проектов
| № п/п| Наименование проекта |
|:----:|----|
| 1 | [Исследование надёжности заёмщиков](#Исследование-надёжности-заёмщиков) |
| 2 | [Исследование объявлений о продаже квартир Санкт-Петербурга](#Исследование-объявлений-о-продаже-квартир-Санкт-Петербурга) |
| 3 | [Выявления прибыльного тарифа для телеком-компании](#Выявления-прибыльного-тарифа-для-телеком-компании) |
| 4 | [Выявление закономерностей, определяющих успешность игры закономерностей](#Выявление-закономерностей-определяющих-успешность-игры-закономерностей) |
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
| Проект на nbviewer.org | [Посмотреть проект - Исследование надёжности заёмщиков](https://nbviewer.org/github/denzzers/semenoff_da23/blob/main/%2301_Project_Исследование_надежности%20заемщиков.ipynb) |

[:house:Перечень проектов](#Перечень-проектов)

## ***Исследование объявлений о продаже квартир Санкт-Петербурга***

**Файл проекта:** [#02_Project_Исследование объявлений о продаже квартир Санкт-Петербурга.ipynb](https://github.com/denzzers/semenoff_da23/blob/main/%2302_Project_Исследование%20объявлений%20о%20продаже%20квартир%20Санкт-Петербурга.ipynb)
|  | **Информация** | 
|:----:|----|
| **Описание проекта** | В вашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — провести исследовательский анализ данных, который поможет установить параметры, влияющие на цену объектов. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. |
| **Используемые библиотеки** | pandas, seaborn, matplotlib |
| **Приобритенные навыки** | <ul><li>Предобработка данных</li><li>Анализ данных</li><li>Инструменты построения графиков: hist(), boxplot(), plot()</li><li>Выборка срезов данных</li><li>Объединение таблиц посредством методов join() и merge()</li><li>Поиск и интерпритация взаимосвязи различных данных</li><li>Автоматизация процесса построения набора графиков</li></ul> |
| Проект на nbviewer.org | [Исследование объявлений о продаже квартир](https://nbviewer.org/github/denzzers/semenoff_da23/blob/main/%2302_Project_Исследование%20объявлений%20о%20продаже%20квартир%20Санкт-Петербурга.ipynb) |
| Файл данных для проекта | [Скачать файл - real_estate_data.csv](https://drive.google.com/file/d/16Y9Fj_4pI9YaJprGulWRNLAtBmdCzulw/view?usp=drive_link) |

[:house:Перечень проектов](#Перечень-проектов)

## ***Выявления прибыльного тарифа для телеком-компании***

**Файл проекта:** [#03_Project_Статический анализ данных_Определение лучшего тарифа оператора сотовой связи.ipynb](https://github.com/denzzers/semenoff_da23/blob/main/%2303_Project_Статический%20анализ%20данных_Определение%20лучшего%20тарифа%20оператора%20сотовой%20связи.ipynb)
|  | **Информация** | 
|:----:|----|
| **Описание проекта** | Необходимо сделать предварительный анализ тарифов "Ультра" и "Смарт" оператора сотовой связи "Мегалайн" на небольшой выборке клиентов, чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. |
| **Используемые библиотеки** | pandas, seaborn, matplotlib, numpy |
| **Приобритенные навыки** | <ul><li>Предобработка данных</li><li>Анализ данных</li><li>Построение гистограмм</li><li>Основы теории вероятности</li><li>Формирование статичесих гипотез, с последующей их проверкой</li></ul> |
| Проект на nbviewer.org | [Выявления прибыльного тарифа для телеком-компании](https://nbviewer.org/github/denzzers/semenoff_da23/blob/main/%2303_Project_Статический%20анализ%20данных_Определение%20лучшего%20тарифа%20оператора%20сотовой%20связи.ipynb) |
| Файл данных для проекта | <ul><li>[Скачать файл - users.csv](https://drive.google.com/file/d/1XBhd53Rsd9V6l-K3LPD7ryo9A1pa6eHU/view?usp=share_link)</li><li>[Скачать файл - calls.csv](https://drive.google.com/file/d/1wgA3_c5NyZQ6NPKVcm_OFbEd_e65pWWS/view?usp=share_link)</li><li>[Скачать файл - messages.csv](https://drive.google.com/file/d/1Ts7Z0HIzW9u95kyyihvHI0vbJiO3Bo9h/view?usp=share_link)</li><li>[Скачать файл - internet.csv](https://drive.google.com/file/d/1dF2TdxO-VX9kO8zOIR1JdXpVhPCI9EwJ/view?usp=share_link)</li><li>[Скачать файл - tariffs.csv](https://drive.google.com/file/d/1ZQEMMqiEJqE9c4XRukiHwwJvqW34cOuz/view?usp=share_link)</li></ul> |

[:house:Перечень проектов](#Перечень-проектов)

## ***Выявление закономерностей, определяющих успешность игры закономерностей***

[:house:Перечень проектов](#Перечень-проектов)

## ***Анализ данных о фондах и инвестициях (SQL)***

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
