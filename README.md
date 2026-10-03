# Systems Analysis & Architecture Portfolio

> Портфолио начинающего системного аналитика: требования, процессы, модели данных, API-контракты и тестовые сценарии на реальном и учебном материале.

## Об авторе

Кирилл. Разработчик с опытом Python/backend, open source и коммерческих проектов.
Развиваюсь в системном анализе: требования, процессы, данные и API.

*English summary: a portfolio of systems analysis artifacts (requirements, BPMN-style flows, ER/state/sequence diagrams, API contracts, acceptance criteria, test cases) built on a real backend project and one hypothetical industrial case.*

---

## Кейсы

| # | Кейс | Тип | Что внутри |
|---|------|-----|-----------|
| 1 | [Team Task Manager: ретроспективный анализ](docs/01-team-task-manager/README.md) | Реальный проект (мой backend) | Роли и права, FR/NFR, user stories + acceptance criteria, ER, state-диаграммы, sequence, фрагмент API-контракта, тест-кейсы |
| 2 | [Система заявок на ТОиР (нефтегаз)](docs/02-cmms-maintenance/README.md) | Учебный, гипотетический | AS-IS / TO-BE, стейкхолдеры, процесс, требования, ER, статусы, интеграции, API, тест-кейсы, риски и открытые вопросы |

## Какие навыки показывает репозиторий

- Сбор и формализация требований: функциональные и нефункциональные, трассировка `BR → FR → TC`.
- Моделирование: процессы (flowchart в стиле BPMN), ER, диаграммы состояний, sequence, use case.
- Проектирование API: ресурсы, методы, коды ошибок, примеры запросов и ответов.
- Acceptance criteria в формате Given / When / Then.
- Тестовые сценарии и проверка полноты требований.
- Честная работа с допущениями: всё, что не подтверждено источником, помечено как гипотеза.

## Как читать

Диаграммы написаны в [Mermaid](https://mermaid.js.org/) и отображаются прямо на GitHub. Каждый кейс самодостаточен: начинайте с раздела «Контекст», затем «Требования», остальное по интересу.

## Структура

```text
systems-analysis-portfolio/
├── README.md
├── ROADMAP.md
├── AGENTS.md
└── docs/
    ├── 01-team-task-manager/
    │   └── README.md
    └── 02-cmms-maintenance/
        └── README.md
```

## Статус

Портфолио развивается. План дальнейших артефактов: [ROADMAP.md](ROADMAP.md).

## Контакты

GitHub: [@f1sherFM](https://github.com/f1sherFM)
