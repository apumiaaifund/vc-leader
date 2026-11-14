# vc-leader — Public Demo

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

## Лицензия

Proprietary. См. LICENSE. Исходный код — по запросу.
