# 👋 Привет, я Данила Шкердин

Backend-разработчик и full-stack энтузиаст. Строю продукты от идеи до продакшена:
Python, гео-обработка данных, мобильный фронтенд и DevOps.

---

## 🔥 Закреплённые проекты

### 🚴 vel.io — территориальная игра для велосипедистов
Полноценный стартап: загружаешь **GPX-трек**, сервис находит замкнутые петли,
превращает их в **полигоны территорий** и закрепляет владение. Пересечения вычитаются,
а захват спонсорских зон приносит самому игроку **доход**.

- **Backend:** Python 3.12, FastAPI, SQLAlchemy 2, slowapi
- **База:** PostgreSQL + **PostGIS**, GeoAlchemy2, Alembic
- **Геометрия:** Shapely, PyProj
- **Frontend:** Vanilla JS, Leaflet.js
- **Mobile:** Capacitor 8 (Android + iOS), фоновая запись GPS
- **Монетизация:** Telegram Stars, спонсорские территории, реферальная система
- **Тесты:** pytest + Playwright e2e

### 🔊 python-allure-notifications
Генерация **Allure-отчёта** в виде диаграммы по результатам тестов
(passed/failed/skipped/broken) и отправка в **Telegram** через Bot API.
*5 ⭐ на GitHub, MIT-лицензия.*

### 🗂️ Mock Manager — управление моками в Kubernetes
Toggle окружение-переменных (`MOCK_ENABLED`, `USE_MOCK`) по всем деплойментам из одного UI.
Щёлкнул — моки включены/выключены.

- **Стек:** Flutter (UI) → FastAPI → kubectl → Teleport → **Kubernetes API**
- **Реал-тайм:** WebSocket + watcher изменений K8s
- **Аудит:** журнал всех изменений (кто, когда, что)
- **Уведомления:** Slack + Band webhooks

### 🚁 TelloVision — управление дроном Ryze Tello
Дрон-контроллер, который **находит твоё лицо** на кадре и сам удерживает
его в центре. UDP-видеопоток, трекинг, векторное управление.

---

## 🛠️ Технологии

**Backend:** Python · FastAPI · SQLAlchemy · Alembic · pytest
**Geodata:** PostGIS · GeoAlchemy2 · Shapely · PyProj
**Frontend / Mobile:** Flutter/Dart · Vanilla JS · Leaflet.js · Capacitor
**DevOps / Infra:** Docker Compose · Kubernetes · kubectl · Teleport
**Testing:** pytest · Allure · Playwright

---

## 📫 Контакты

- GitHub: [@danilashkerdin](https://github.com/danilashkerdin)
- Email: danila.shkerdin.01@mail.ru

> 💡 Открыт к обсуждению кода, ревью и здоровой критике.