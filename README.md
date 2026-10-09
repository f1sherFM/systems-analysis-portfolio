# Backend Engineer & Systems Analyst Portfolio

> Портфолио инженера, который умеет и спроектировать систему (требования, модели, контракты, SLO), и построить её руками (код, тесты, CI, прод). Фокус: backend на Python и системный анализ для промышленных/телеметрических систем.

## Об авторе

Кирилл. Backend-разработчик (Python), с открытым кодом в проде, плюс системный анализ: требования, процессы, модели данных, API-контракты, эксплуатационные SLA/SLO.

*English summary: a portfolio combining production backend engineering (FastAPI/Django, tests, CI, deployment) with systems analysis artifacts (requirements, ER/state/sequence diagrams, API contracts, acceptance criteria, test cases, SLOs and runbooks).*

---

## Кейсы

| # | Кейс | Тип | Что внутри |
|---|------|-----|-----------|
| 1 | [AirTrace v2: телеметрия, алертинг, эксплуатация](docs/03-airtrace-telemetry/README.md) | Реальный production-проект автора (FastAPI + Postgres + Redis) | Полный цикл: ADR, FR/NFR → код → автотесты, SLO с порогами алертов, incident-Runbook, контракт API |
| 2 | [Team Task Manager: ретроспективный анализ](docs/01-team-task-manager/README.md) | Реальный backend автора (Django 5 + DRF) | Матрица прав по `permissions.py`, FR/NFR, ER, state-диаграммы, sequence, API-контракт, трассировка «требование → тест → код» |
| 3 | [Система заявок на ТОиР (нефтегаз)](docs/02-cmms-maintenance/README.md) | Учебный, гипотетический | AS-IS / TO-BE, стейкхолдеры, процесс, требования, ER, статусы, интеграции, API, тест-кейсы, риски |

Кейс 1 — флагманский: он показывает связку навыков, которой обычно не хватает ни у «чистых» аналитиков, ни у «чистых» разработчиков — от формулировки требования до работающего мониторинга на проде.

## Какие навыки показывает репозиторий

- **Инженерия:** production-бэкенды (FastAPI, Django REST Framework), модульная архитектура с ADR, автотесты и контрактные тесты, CI, Docker-деплой, Sentry/метрики.
- **Сбор и формализация требований:** функциональные и нефункциональные, трассировка `BR → FR → TC → код`.
- **Моделирование:** ER, диаграммы состояний, sequence, use case, процессы в стиле BPMN.
- **Проектирование API:** ресурсы, методы, коды ошибок, идемпотентность, примеры запросов и ответов.
- **Эксплуатация как часть анализа:** NFR → SLO → метрики → пороги алертов → Runbook.
- Acceptance criteria в формате Given / When / Then, подтверждённые автотестами.
- Честная работа с допущениями: всё, что не подтверждено источником, помечено как гипотеза.

## Как читать

Диаграммы написаны в [Mermaid](https://mermaid.js.org/) и отображаются прямо на GitHub. Каждый кейс самодостаточен: начинайте с раздела «Контекст», затем «Требования», остальное по интересу. В кейсах 1–2 ссылки ведут в открытые репозитории с кодом — любую строку документов можно сверить с реализацией.

## Структура

```text
portfolio/
├── README.md
├── ROADMAP.md
└── docs/
    ├── 01-team-task-manager/    # кейс 2 в таблице (Django)
    ├── 02-cmms-maintenance/     # кейс 3 в таблице (ТОиР)
    └── 03-airtrace-telemetry/   # кейс 1 в таблице (флагман, FastAPI)
```

## Связанные репозитории

- [AirTrace-v2](https://github.com/f1sherFM/AirTrace-v2) — прод: nande.webhop.me
- [Team_Task_Manager](https://github.com/f1sherFM/Team_Task_Manager) — Django 5 + DRF, CI с coverage-гейтом
- [Профиль на GitHub](https://github.com/f1sherFM) — остальные проекты (интеграционный контур NANDE_Ecosystem, учебные и инструментальные репозитории)

## Статус

Портфолио развивается. План дальнейших артефактов: [ROADMAP.md](ROADMAP.md).

## Контакты

GitHub: [@f1sherFM](https://github.com/f1sherFM)
