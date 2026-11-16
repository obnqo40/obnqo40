<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/hero-dark.svg">
  <img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/hero-light.svg" alt="Dmitry / obnqo40 — Full-stack developer. Web, automation, Android." width="100%">
</picture>

# Привет, я Дмитрий

**Full-stack / Backend Developer** · веб-приложения, Python-автоматизация и Android.

Превращаю повседневные задачи в приложения: от записи на услугу и школьного расписания до складской комплектации и управления сообществом. В проектах работаю с интерфейсом, данными и интеграциями; отдельно уделяю внимание обработке ошибок и понятной документации.

**[Демо](#открыть-в-браузере)** &nbsp; / &nbsp; **[Проекты](#избранные-проекты)** &nbsp; / &nbsp; **[Разборы](#за-пределами-веба)** &nbsp; / &nbsp; **[Каталог](docs/projects.md)** &nbsp; / &nbsp; **[English](README.en.md)**

## Открыть в браузере

**[Business Leads ↗](https://business-leads-template.vercel.app/)** &nbsp; · &nbsp; **[ЗАО «МЫС» ↗](https://obnqo40.github.io/zao_mys/)** &nbsp; · &nbsp; **[Моё Расписание ↗](https://moe-raspisanie.vercel.app/)**

<sub><a href="docs/demos.md">Все адреса и что посмотреть в каждом демо</a> · <a href="docs/code-tour.md">Маршрут по коду</a></sub>

## Избранные проекты

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>01 / Business Leads</h3>
      <a href="https://business-leads-template.vercel.app/"><img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/business-leads.jpg" alt="Демо Business Leads — конфигурация Fresh Cut" width="100%"></a>
      <p><strong>От выбора услуги до заявки владельцу.</strong></p>
      <p>Сайт услуг с единым конфигом, серверной проверкой данных и независимой доставкой в Telegram, MAX, email и Google Sheets.</p>
      <p><code>Next.js</code> <code>React</code> <code>TypeScript</code></p>
      <p><strong><a href="https://business-leads-template.vercel.app/">Демо ↗</a></strong> · <a href="https://github.com/obnqo40/business-leads-template">Код</a> · <a href="docs/business-leads.md">Разбор</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>02 / ЗАО «МЫС»</h3>
      <a href="https://obnqo40.github.io/zao_mys/"><img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/zao-mys.jpg" alt="Демо промышленного сайта ЗАО МЫС" width="100%"></a>
      <p><strong>Промышленный контент в понятном интерфейсе.</strong></p>
      <p>Многостраничный сайт: каталог продукции, галереи, страницы компании, качества, новостей и контактов.</p>
      <p><code>HTML / CSS</code> <code>JavaScript</code> <code>Alpine.js</code></p>
      <p><strong><a href="https://obnqo40.github.io/zao_mys/">Демо ↗</a></strong> · <a href="https://github.com/obnqo40/zao_mys">Код</a> · <a href="docs/zao-mys.md">Разбор</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>03 / Моё Расписание</h3>
      <a href="https://moe-raspisanie.vercel.app/"><img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/scheduling.jpg" alt="Демо приложения Моё Расписание" width="100%"></a>
      <p><strong>Школьное расписание и работа с Excel.</strong></p>
      <p>Уроки, проверка пересечений, генерация и локальное хранение. Учебная V1 с PWA-оболочкой; серверная авторизация запланирована для V2.</p>
      <p><code>JavaScript</code> <code>IndexedDB</code> <code>PWA</code></p>
      <p><strong><a href="https://moe-raspisanie.vercel.app/">Демо ↗</a></strong> · <a href="https://github.com/obnqo40/Moe-raspisanie">Код</a> · <a href="docs/scheduling.md">Разбор</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>04 / Full-stack Lab</h3>
      <a href="https://github.com/obnqo40/full-stack-lab#readme"><img src="https://raw.githubusercontent.com/obnqo40/obnqo40/main/assets/full-stack-lab.svg" alt="Схема лаборатории: Nginx, два контейнера со страницами и отдельный PostgreSQL" width="100%"></a>
      <p><strong>Несколько сервисов в одном окружении.</strong></p>
      <p>Nginx распределяет запросы между двумя контейнерами со статическими страницами. PostgreSQL — отдельный сервис учебного стенда.</p>
      <p><code>Docker Compose</code> <code>Nginx</code> <code>PostgreSQL</code></p>
      <p><strong><a href="https://github.com/obnqo40/full-stack-lab#запуск">Запуск локально →</a></strong> · <a href="https://github.com/obnqo40/full-stack-lab">Код</a></p>
    </td>
  </tr>
</table>

**Любите разбираться в устройстве?** [Начните с API заявок, генератора расписания и общей логики страниц →](docs/code-tour.md)

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
