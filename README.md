<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/hero-dark.svg">
  <img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/hero-light.svg" alt="Dmitry / obnqo40 — Full-stack developer. Web, automation, Android." width="100%">
</picture>

# Привет, я Дмитрий

**Full-stack / Backend Developer** · веб-приложения, Python-автоматизация и Android.

Превращаю повседневные задачи в приложения: от записи на услугу и школьного расписания до складской комплектации и управления сообществом. В проектах работаю с интерфейсом, данными и интеграциями; отдельно уделяю внимание обработке ошибок и понятной документации.

**[Проекты](#избранные-проекты)** &nbsp; / &nbsp; **[Разборы разработок](#за-пределами-веба)** &nbsp; / &nbsp; **[Весь каталог](docs/projects.md)** &nbsp; / &nbsp; **[English](README.en.md)**

## Избранные проекты

### 01 / Business Leads

**Сайт для малого бизнеса с приёмом заявок в несколько каналов.**

Один конфиг задаёт услуги, цены, контакты и оформление. Сервер проверяет заявку и параллельно передаёт её в подключённые Telegram, MAX, email и Google Sheets. У каждого адаптера свой результат и таймаут: сбой одного канала не прерывает остальные.

`Next.js` `React` `TypeScript` `API Routes`

**[Открыть демо ↗](https://business-leads-template.vercel.app/)** · [Код](https://github.com/obnqo40/business-leads-template) · [Архитектура и решения](docs/business-leads.md)

<details>
  <summary>Посмотреть интерфейс</summary>
  <p><img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/business-leads.jpg" alt="Главная страница демо Business Leads — Fresh Cut" width="100%"></p>
</details>

### 02 / Моё Расписание

**Электронный помощник для управления школьным расписанием.**

Редактирование уроков, проверка пересечений, генерация расписания, импорт и экспорт Excel. Учебная V1 работает с локальными данными в браузере и PWA-оболочкой. Серверная авторизация относится к планируемой V2.

`JavaScript` `IndexedDB` `Excel` `PWA`

**[Открыть демо ↗](https://moe-raspisanie.vercel.app/)** · [Код](https://github.com/obnqo40/Moe-raspisanie) · [Разбор V1](docs/scheduling.md)

<details>
  <summary>Посмотреть интерфейс</summary>
  <p><img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/scheduling.jpg" alt="Главная страница демо Моё Расписание" width="100%"></p>
</details>

### 03 / ЗАО «МЫС»

**Многостраничный интерфейс промышленного предприятия.**

Каталог продукции, страницы компании и качества, новости, контакты и документы. Общие стили и сценарии объединяют страницы; галереи, мобильная навигация и анимации помогают работать с насыщенным контентом.

`HTML` `CSS` `JavaScript` `Alpine.js` `Tailwind CSS`

**[Посмотреть проект ↗](https://github.com/obnqo40/zao_mys#readme)** · [Страницы и запуск](https://github.com/obnqo40/zao_mys#запуск)

### 04 / Full-stack Lab

**Небольшая лаборатория контейнеров и балансировки запросов.**

Nginx направляет запросы к двум контейнерам со статическими HTML-страницами. PostgreSQL запущен отдельным сервисом для дальнейших экспериментов. Схема, запуск и границы учебного стенда описаны в README.

`Docker Compose` `Nginx` `PostgreSQL`

**[Открыть лабораторию ↗](https://github.com/obnqo40/full-stack-lab#readme)**

## За пределами веба

Локальные разработки, для которых здесь опубликованы описания устройства и реализованных сценариев.

| Проект | Что в нём интересно | Разбор |
| :--- | :--- | :--- |
| **Skladmen WMS** | Android-приложение для комплектации заказов: Room, CSV, поиск по штрихкоду, архив | [Kotlin / Compose →](docs/skladmen.md) |
| **MAXGRAM** | Кастомизация открытого Telegram Android: темы, навигация, локальные инструменты | [Android fork →](docs/maxgram.md) |
| **Vanta Market** | Асинхронные боты, общий остаток в SQLite, состояния заказа и сверка доставки | [Python / SQLite →](docs/automation.md#vanta-market) |
| **SWAGA BOT** | Жизненный цикл голосовых комнат Discord, права доступа и восстановление после перезапуска | [Python / Discord →](docs/automation.md#swaga-bot) |
| **VK Consent Monitor** | Мониторинг разрешённых профилей через официальный API и обработка переходов состояния | [Python / API →](docs/automation.md#vk-consent-monitor) |

## Инструменты в моих проектах

| Направление | Технологии | Где посмотреть |
| :--- | :--- | :--- |
| Веб и API | TypeScript, React, Next.js, HTML, CSS | [Business Leads](https://github.com/obnqo40/business-leads-template) · [Моё Расписание](https://github.com/obnqo40/Moe-raspisanie) |
| Автоматизация | Python, asyncio, aiohttp, aiogram, discord.py | [Разбор ботов](docs/automation.md) |
| Android | Kotlin, Java, Compose, Room, Hilt, Coroutines | [Skladmen](docs/skladmen.md) · [MAXGRAM](docs/maxgram.md) |
| Данные и окружение | SQLite, IndexedDB, PostgreSQL, Docker Compose, Nginx | [Лаборатория](https://github.com/obnqo40/full-stack-lab) |

В разработке для меня важны понятные границы компонентов, проверка входных данных, сохранность состояния и честное описание ограничений. Планы и локальные прототипы в этом портфолио помечены отдельно от опубликованного кода.

---

**Хотите обсудить проект?** Начните с [репозитория](https://github.com/obnqo40?tab=repositories) и его Issues.

<sub>Ещё работы и учебные эксперименты — в <a href="docs/projects.md">полном каталоге</a>.</sub>
