<div align="center">
  <img src="assets/banner.webp" alt="Onlyuncia — бизнес- и системный анализ">
</div>

<img src="assets/h-about.webp" alt="Обо мне" width="100%" />

**Фулстек-аналитик (БА/СА).**
 
Проектирую цифровые сервисы: разбираю процессы и данные, формулирую требования, описываю взаимодействие систем и довожу решения до понятных команде сценариев и критериев приёмки.
 
**Фокус:** процессы · данные · требования · взаимодействие систем · критерии приёмки

<img src="assets/h-grafio.webp" alt="Проект Grafio" width="100%" />

[**Grafio**](https://github.com/onlyuncia/grafio-product-docs) — аналитический сервис для продавцов маркетплейсов. Проектировал его с нуля: от подключения кабинетов и синхронизации данных до раздела РНП с дневными и недельными показателями, товаров, планов и редактируемого дашборда. Отдельно проработал контроль расчётов, роли сотрудников и административный процесс изменения методики.

| | |
|:--|:--|
| [**Требования**](https://github.com/onlyuncia/grafio-product-docs/tree/main/docs/requirements) | требования и критерии приёмки |
| [**Архитектура**](https://github.com/onlyuncia/grafio-product-docs/tree/main/docs/architecture) | C4, sequence, ADR |
| [**Процессы**](https://github.com/onlyuncia/grafio-product-docs/blob/main/docs/processes/bpmn-index.md) | BPMN: AS-IS и TO-BE |
| [**Данные**](https://github.com/onlyuncia/grafio-product-docs/tree/main/docs/data) | модель данных и описание показателей |
| [**API**](https://github.com/onlyuncia/grafio-product-docs/blob/main/docs/api/openapi.json) | OpenAPI-контракт |
| [**Прототип**](https://github.com/onlyuncia/grafio-product-docs/tree/main/prototype) | демонстрационный прототип |
| [**Экраны**](https://github.com/onlyuncia/grafio-product-docs/tree/main/screenshots) | скриншоты основных разделов |

[**MarginPilot**](https://github.com/onlyuncia/marginpilot-product-docs) — внутренняя система для оценки экономики SKU, управления ценами и участием товаров в акциях Ozon. Я собирал требования и проектировал функции, которые помогают менеджеру проверить цену до отправки, осознанно подтвердить исключение и сверить результат по каждому SKU. В кейсе также показано, как плановая экономика сопоставляется с продажами и фактическими расходами.

| | |
|:--|:--|
| [**Требования**](https://github.com/onlyuncia/marginpilot-product-docs/tree/main/docs) | функции, ограничения и критерии приёмки |
| [**Архитектура**](https://github.com/onlyuncia/marginpilot-product-docs/blob/main/docs/01-SYSTEM-ARCHITECTURE.md) | контейнерная диаграмма C4 и границы системы |
| [**Процессы**](https://github.com/onlyuncia/marginpilot-product-docs/blob/main/docs/02-PROCESS-AS-IS-TO-BE.md) | BPMN: до и после внедрения |
| [**Сценарии**](https://github.com/onlyuncia/marginpilot-product-docs/blob/main/docs/10-USE-CASES.md) | цены, акции и план-факт по SKU |
| [**Данные**](https://github.com/onlyuncia/marginpilot-product-docs/blob/main/docs/14-DATABASE-SCHEMA.dbml) | проектная модель PostgreSQL в DBML |
| [**API**](https://github.com/onlyuncia/marginpilot-product-docs/blob/main/docs/15-OPENAPI.json) | реконструированный OpenAPI-контракт |
| [**Прототип**](https://onlyuncia.github.io/marginpilot-product-docs/#demo) | интерактивное демо на вымышленных данных |

[**StockFlow**](https://github.com/onlyuncia/stockflow-product-docs) — бэкофис-система для планирования пополнения запасов на маркетплейсах. Во время работы в консалтинговой компании я разобрал процесс подсорта и проработал расчёт потребности, распределение доступного товара между площадками и планирование закупки. Менеджер может принять предложение, изменить количества или отказаться от него. В кейсе я связал требования, процессы, модель данных и API, сохранив историю расчёта и решения.

| | |
|:--|:--|
| [**Требования**](https://github.com/onlyuncia/stockflow-product-docs/blob/main/docs/03-FUNCTIONAL-REQUIREMENTS.md) | функции, ограничения и критерии приёмки |
| [**Архитектура**](https://github.com/onlyuncia/stockflow-product-docs/blob/main/docs/06-ARCHITECTURE.md) | C4: контекст, контейнеры и компоненты |
| [**Процессы**](https://github.com/onlyuncia/stockflow-product-docs/blob/main/docs/01-PROCESS-AS-IS-TO-BE.md) | BPMN: до и после внедрения |
| [**Сценарии**](https://github.com/onlyuncia/stockflow-product-docs/blob/main/docs/04-USE-CASE.md) | потребность, распределение и решение менеджера |
| [**Данные**](https://github.com/onlyuncia/stockflow-product-docs/blob/main/docs/07-DATA-MODEL.md) | модель PostgreSQL, Master ERD и DBML |
| [**API**](https://github.com/onlyuncia/stockflow-product-docs/blob/main/docs/09-OPENAPI.json) | реконструированный OpenAPI-контракт |
| [**Прототип**](https://github.com/onlyuncia/stockflow-product-docs/tree/main/prototype) | демонстрационный интерфейс на вымышленных данных |

<img src="assets/h-tools.webp" alt="Инструменты" width="100%" />

| | |
|:--|:--|
| **Задачи и документация** | Jira, Confluence |
| **Процессы** | BPMN 2.0 |
| **Диаграммы** | PlantUML (Use Case, sequence, C4), Mermaid, draw.io |
| **Данные** | SQL (PostgreSQL), Excel / Google Sheets, ERD, логические модели, диаграммы состояний |
| **API и интеграции** | REST / JSON, OpenAPI 3.1, Swagger, Postman, брокеры сообщений |
| **Дизайн и схемы** | Figma, Miro |
| **Нейросети** | ChatGPT, Claude, Cursor: прототипирование по моим требованиям и сценариям |
| **Версионирование** | Git, GitHub |
 
<br/>
<img src="assets/divider.webp" alt="" width="100%" />

