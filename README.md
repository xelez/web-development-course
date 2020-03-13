# Курс Web-программирования для ПГНИУ, г. Пермь (Версия 2019)

## О курсе

### Цель курса

Веб-программирование занимает существенную часть в мире современной разработки. Многие студенты делают веб-приложения в рамках НИР или занимаются этим на первой работе.

Веб-приложения, создаваемые в рамках НИР, чаще всего нетиповые приложения. На работе студенты работают с современными технологиями веб-разработки: SPA приложениями, JS фреймворками, используют самые разные языки на серверной части.

Цели курса: систематизировано изучить веб-разработку от теоретического фундамента до обзора технологий веб-разработки, а также получить практические навыки как традиционной, так и современной веб-разработки.

### Тезисы

1. Теория впереди примеров.
2. Акцент на клиентскую часть.
3. В вёрстке нужны только основы.
4. Важны как традиционные, так и современные технологии.
5. Курс ТРРП изучается параллельно.
6. Больше обзора, чем конкретных технологий.
7. Маленькие лабораторные вместо большого проекта.
8. Решение одних задач разными инструментами.

### Комментарии к тезисам

1. Сначала рассматриваем, что происходит, зачем, а потом примеры реализации. Начинаем с теории клиент-серверных приложений, немного про запросы, протоколы. В языке с основ, парадигмы, особенностей, синтаксиса. Больше внимания спецификациям.
2. Серверная часть веб-приложения -- это обычное приложение. Оно мало чем отличается от веб-сервиса, который мало чем отличается от сервиса (что студенты проходят на ТРРП). Оно может быть сделано на любом языке программирования. Студенты уже умеют программировать, уже знают какие-то языки программирования, у многих есть “свой любимый язык”, умеют работать с БД. Требуется лишь знать основные подходы, паттерны, инструменты.
3. С одной стороны, вёрстка -- сложная и большая тема. Особенно, если углубляться, изучать методологии, правила хорошего тона, семантику, доступность, знать как традиционные, так и актуальные походы. Вёрстку нельзя изучить за небольшое число занятий. С другой стороны, самостоятельная верстка занимает много времени, в то время как при разработке у студентов акцент на работающий прототип, а не уникальный дизайн.
4. Изучать только традиционный веб -- плохо, для решения в НИР и на работе им понадобится современный. Но изучать сразу современный без понимания основ также нельзя, это приводит к большему непониманию.
5. Одновременно проходит курс ТРРП (Технологии Разработки Распределённых Приложений), на котором изучаются клиент-серверные приложения.
6. Важно, чтобы студенты представляли, какие есть инструменты в мире веб-разработки, когда и какие лучше применять и могли решать широкий спектр задач, углубляясь в нужные им технологии.
7. Командная разработка большого проекта -- это очень хорошо. Но времени и возможностей разработать командой проект нет. При этом требуется попробовать различные технологии и подходы, решить разные независимые задачи. Возможно, такой вариант можно сделать альтернативным.
8. Решение одних и тех же задач как традиционным, так и современным подходом, позволит лучше почувствовать разницу между ними.

## План курса

### План по блоками

#### Блок 1: Введение в веб-разработку. 
Входной контроль.  
Основные понятия веб-разработки, краткая история веба, план курса и его места в веб-разработке. Инструменты. Ресурсы.  
**Лабораторные работы:** отсутствуют.

#### Блок 2: Традиционная клиентская часть.
Языки HTML и CSS. Основы верстки. Чистый JavaScript. Немного про jQuery. UI фреймворки. 
**Лабораторные работы:** вёрстка, мини-игрушка на чистом javascript. 

#### Блок 3: Серверная часть.
Рассматриваем, что такое серверная часть приложения, обзор технологий (подходов, языков, фреймворков).  
Подходы к разработке приложения: CMS, Frameworks, с нуля.  
PHP + какой-нибудь другой язык (python + flask).  
Подходы к аутентификации и авторизации. Затрагиваем вопросы безопасности. Начинаем говорить про AJAX и API.  
**Лабораторная работа:** простой многостраничный сайт с crud операциями с и без ajax.  
**Доклады:** Asp.NET, Java Spring и другие фреймворки.  

#### Блок 4: Современная клиентская часть.
Инструменты разработки: NodeJS, пакеты и пакетный менеджер (npm, yarn), сборка клиентской части (gulp, webpack), препроцессоры (Less, Sass) и постпроцессоры (PostCSS, PostHTML), транслиптеры (Babel, TypeScript), линтеры.  
SPA приложения. Клиентский роутинг.  
Фреймворки клиентской части (React, Vue, Angular).  
Другие протоколы: WebSocket, WebRTC  
**Лабораторные работы:** повторение предыдущего задания уже в виде SPA приложения. Разработка маленького чата.  

#### Блок 5: Развёртывание.
С одной стороны, работа с сервером, unix, сетями, DNS и др -- не веб-разработка, но с другой стороны это нужно для полного понимания и завершения работы над веб-приложением.  
Где может быть развёрнуто веб-приложение: хостинг, VPS, выделенный сервер, облако, облако.  
Кратко о том, как развернуть веб-приложение на VPS на Linux, привязать домен, HTTPS.  
**Лабораторные работы:** ?  
**Доклады:** Windows + IIS, serverless, cloud

#### Блок 6: Что ещё есть в веб-разработке? Обзорно.  
SEO, Тестирование (unit, e2e), 
Мобильная и десктоп разработка: Electron, ReactNative, NativeScript.  
WebGL, WebAssembly, PWA.  

### Подробный план

## Список тем к экзамену
1. Понятия: Распределенное приложение, Клиент-серверное приложение, Веб-приложение. Архитектура веб-приложений;
1. Понятия: IP адрес, Доменное имя, Доменная зона, DNS; Структура URL;
1. HTTP(S), Структура HTTP, Основные HTTP методы и группы HTTP статусов;
1. HTML, Структура HTML документа, Основные элементы, CSS;
1. Язык JavaScript, JSON;
1. Подходы к серверной части. Понятие CMS;
1. Понятия Шаблонизатор, Роутер (маршрутизатор);
1. Понятия Идентификация, Аутентификация, Авторизация и способы аутентификации; Сессия, HTTP Cookie, JWT;
1. Подход AJAX;
1. Понятие Транспайлер. NodeJS. Назначение CSS препроцессора, Babel, Linter, Formatter, DevServer и др. инструментов;
1. SPA, преимущества, проблемы подхода;
1. Понятия SEO, l10n, i18n, a12y;
1. Развёртывание, On-Premise, IaaS, PaaS, SaaS, FaaS.

## Экзамен
Экзамен - 40 баллов.
- 20 баллов - теоретический тест.
- 20 баллов - нормализованная оценка за все остальные лабораторные работы.
+ 10 баллов - бонус за выполнение дополнительных заданий. Позволяют набрать больше 100 баллов или покрыть нехватку баллов.

## Примечания

## Ресурсы

## Заметки на будущее

1. Уделить чуть больше внимания вёрстке. ~ на одно занятие;
1. Найти небольшой интерактивный курс по JS с тестом (либо сделать его), так как изучить язык за лекцию тяжело;
1. Аналогично по CSS;
1. Добавить лекцию на архитектуру современных веб-приложений подобно https://tprg.ru/shRk;
1. Подробнее рассказать про подходы к аутентификации с теоретической точки зрения. Digest, token, OAuth (1, 2). Практику по аутентификации вынести на практику
1. По результатам опроса студентам не понравился вариант с более формализованными, но автоматически проверяемыми лабораторными работами.   
Тем не менее предлагается сделать авто-проверяемые лабораторные (на основе e2e). Это позволит значительно съэкономить время на практиках, и выдавать на них больше материала;
1. Рассказать больше про PHP;
1. Больше сравнения технологий (языков, фреймворков);
1. Возможно, добавить микро-задание (или сделать вместе на практике) по сборке веб-приложений на Webpack.

