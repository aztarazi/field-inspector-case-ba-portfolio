# Модуль «Полевой инспектор» - пакет артефактов бизнес-аналитика

Демонстрационный сквозной кейс бизнес-аналитика: автоматизация полевого этапа инспекций и интеграция мобильного приложения инспектора с LIMS (планшет -> REST API -> LIMS -> БД MS SQL Server -> QR-код на пломбу).

Кейс вымышленный и обезличенный, собран для портфолио: показывает работу аналитика от бизнес-проблемы до плана внедрения.

## Живой прототип

**[Открыть интерактивный прототип](https://aztarazi.github.io/field-inspector-case-BA-portfolio/)**

Рабочий макет сквозного потока: форма забора пробы -> JSON-payload для REST API -> проверочный SQL-запрос -> генерация QR-кода. Можно заполнить форму и нажать «Зафиксировать пробу».

## Состав артефактов (порядок чтения)

| Этап | Артефакт | Что это |
|---|---|---|
| 0. Термины | [glossary.docx](artefacts/glossary.docx) | Глоссарий и словарь данных + мини-словарь `dbo.Samples`, HTTP-коды |
| 1. Бизнес-анализ | [brd.docx](artefacts/brd.docx) | Документ бизнес-требований: проблема, цели, обоснование |
| 2. Процессы | [AS-IS](artefacts/as-is_with_overlays.png) · [TO-BE](artefacts/to-be_with_overlays.png) | BPMN-схемы текущего и целевого процессов |
| 2. Процессы | [gap-analysis.docx](artefacts/gap-analysis.docx) | Анализ разрывов AS-IS -> TO-BE |
| 3. Требования | [frd.docx](artefacts/frd.docx) | Функциональные требования + use cases с привязкой к BRD (BR-xx) |
| 3. Требования | [user-stories.docx](artefacts/user-stories.docx) | Пользовательская история и критерии приёмки (Given-When-Then) |
| 4. Интеграция | [data-mapping.docx](artefacts/data-mapping.docx) | Спецификация интеграции API-04: маппинг полей, HTTP-коды |
| 5. План | [backlog-product-roadmap.docx](artefacts/backlog-product-roadmap.docx) | Roadmap по спринтам + бэклог в Jira-стиле с трассировкой к BR |

## Стек и навыки в кейсе

Анализ требований · BPMN 2.0 (AS-IS / TO-BE) · User Stories / Use Cases · REST API · Data Mapping · SQL · Jira-бэклог · трассируемость требований · прототипирование.
