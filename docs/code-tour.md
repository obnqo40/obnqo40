[← Профиль](https://github.com/obnqo40) · [Все проекты](projects.md) · [Демо](demos.md)

# Маршрут по коду

Короткие маршруты для знакомства с реализацией публичных проектов: задача, основные файлы и решение, на которое стоит обратить внимание.

## 1. Как заявка проходит через сервер

**Проект:** [Business Leads](business-leads.md).

| Порядок | Файл | На что посмотреть |
| :--- | :--- | :--- |
| 1 | [`business.config.ts`](https://github.com/obnqo40/business-leads-template/blob/main/src/config/business.config.ts) | Контент, услуги, способы связи и каналы доставки задаются в одном месте |
| 2 | [`LeadForm.tsx`](https://github.com/obnqo40/business-leads-template/blob/main/src/components/LeadForm.tsx) | Форма, состояние отправки и показ результата |
| 3 | [`api/leads/route.ts`](https://github.com/obnqo40/business-leads-template/blob/main/app/api/leads/route.ts) | Разбор HTTP-запроса, предел размера тела и публичные ответы |
| 4 | [`lead.schema.ts`](https://github.com/obnqo40/business-leads-template/blob/main/src/server/lead.schema.ts) | Проверка типов, допустимых значений и согласия; honeypot |
| 5 | [`delivery.ts`](https://github.com/obnqo40/business-leads-template/blob/main/src/server/delivery.ts) | Независимые результаты адаптеров, таймауты и частичный успех |

**Ключевое решение:** отказ одного внешнего канала не прерывает попытки в остальных. Постоянная очередь и повторная доставка потребовали бы отдельного слоя хранения.

## 2. Как браузер работает с расписанием

**Проект:** [Моё Расписание](scheduling.md).

| Файл | На что посмотреть |
| :--- | :--- |
| [`dashboard.js`](https://github.com/obnqo40/Moe-raspisanie/blob/main/dashboard.js) | IndexedDB, изменение уроков, проверка пересечений, генерация, импорт и экспорт Excel |
| [`service-worker.js`](https://github.com/obnqo40/Moe-raspisanie/blob/main/service-worker.js) | Кэширование статических ресурсов PWA-оболочки |
| [`README.md`](https://github.com/obnqo40/Moe-raspisanie/blob/main/README.md) | Граница клиентской V1 и направление серверной V2 |

**Ключевой вывод:** клиентское хранилище удобно для учебного локального приложения, а доверенную авторизацию нужно строить на сервере.

## 3. Как несколько страниц получают общее поведение

**Проект:** [ЗАО «МЫС»](zao-mys.md).

| Файл | На что посмотреть |
| :--- | :--- |
| [`assets/site.js`](https://github.com/obnqo40/zao_mys/blob/main/assets/site.js) | Индикатор прокрутки, анимации, подготовка изображений, контактная форма |
| [`assets/site.css`](https://github.com/obnqo40/zao_mys/blob/main/assets/site.css) | Общие состояния и эффекты оформления |
| [`products.html`](https://github.com/obnqo40/zao_mys/blob/main/products.html) | Карточки каталога, состояние галереи и lightbox |

**Ключевое решение:** общие эффекты вынесены в переиспользуемый слой, а состояния конкретной галереи принадлежат странице.

## 4. Как запрос попадает в один из контейнеров

**Проект:** [Full-stack Lab](https://github.com/obnqo40/full-stack-lab#readme).

Начните с [`compose.yaml`](https://github.com/obnqo40/full-stack-lab/blob/main/compose.yaml), затем откройте [`nginx.conf`](https://github.com/obnqo40/full-stack-lab/blob/main/nginx.conf). Обратите внимание на имена сервисов в upstream и монтирование файлов в контейнеры. PostgreSQL включён как отдельный сервис; связи с HTML-страницами у него пока нет.

---

У локальных проектов опубликованы отдельные описания решений: [Room и Compose в Skladmen](skladmen.md), [развитие Android-форка MAXGRAM](maxgram.md), [состояния заказов и ботов](automation.md).
