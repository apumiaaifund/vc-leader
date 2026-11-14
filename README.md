# vc-leader — Public Demo

## За 30 секунд

**Что это:** vc-leader: SD-JWT VC backend для eIDAS 2.0. Выпуск, верификация, селективное раскрытие.

**Кому:** EU-провайдеры identity, eIDAS 2.0 — но для РФ-экспорта закрыто санкциями.

**Что доказано:** 14 тестов.

**Чего не доказано (честно):** EU-рынок закрыт для IT-услуг из РФ.

---



**Verifiable Credentials backend** — SD-JWT VC, OpenID4VP 1.0, HAIP. On-premise, offline verification.

## Что делает

- **SD-JWT VC** — Selective Disclosure JWT Verifiable Credentials (IETF draft)
- **OpenID4VP 1.0** — OpenID for Verifiable Presentations
- **HAIP** — High Assurance Interoperability Profile
- **14 тестов** — SD-JWT, holder binding, VP flow
- **On-premise** — без вендор-лока, без облака

## Проблема

W3C VC и eIDAS 2.0 требуют асимметричной подписи и SD — но существующие решения (Microsoft Entra Verified ID, IBM Verify) привязаны к облаку. Для regulated-контура (банк, госсектор) это блокер.

## Компоненты

| Модуль | Что |
|---|---|
| SD-JWT VC | issue / verify, selective disclosure |
| OpenID4VP | presentation request / response |
| HAIP | High Assurance Interoperability Profile |
| Verifier | offline, без API вендора |

## Тесты

14 passed — SD-JWT, holder binding, VP flow, HAIP compliance.

## Цена

| Уровень | Цена | Кому |
|---|---|---|
| Пилот | 400–700 тыс ₽ / 2 мес | EdTech, HR-tech |
| Годовая лицензия | 1,5–3 млн ₽ | Госсектор, финтех |
| Интеграция | 300–500 тыс ₽ | Консалтинг |

Контакт: apumiaaifund@gmail.com


## Data integrity

**No synthetic data in production.** External sources are documented in `sources.yaml` (Private repo) with official URLs, real verification dates, and status. No fabricated dates. Demo artifacts are clearly marked as examples.

**Никакой синтетики в продакшене.** Внешние источники — в `sources.yaml` (Private репо) с официальными URL, реальными датами, статусом. Ни одной придуманной даты. Demo — помечены как примеры.


## Лицензия

Proprietary. См. LICENSE. Исходный код — по запросу.
