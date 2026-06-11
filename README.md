# NotificationPlayer

Android-приложение для озвучивания уведомлений через Piper TTS.

Скачайте APK в разделе [Releases](../../releases).

## 🎮 Живое демо

[![Открыть демо](https://img.shields.io/badge/▶%20Открыть%20демо-5b8eff?style=for-the-badge&logo=android&logoColor=white)](https://dictovod.github.io/NotificationPlayer/)

# 🔔 NotificationPlayer

> **Превратите любое уведомление в голосовое сообщение**  
> *Turn any notification into a voice announcement*

---

## 🇷🇺 Русский

### Что это?

**NotificationPlayer** — Android-приложение, которое перехватывает уведомления на вашем телефоне, обрабатывает их через облачный сервер и озвучивает результат живым голосом (TTS Piper — Irina / Ruslan).

Никаких касаний экрана. Телефон говорит сам.

### Для кого это?

| Сфера | Сценарий |
|-------|----------|
| 💳 **Финансы** | Банковские переводы, пополнения, СБП, ЮMoney — сумма и отправитель вслух |
| 🛒 **Торговля и бизнес** | Новый заказ, оплата от клиента, статус отгрузки — руки заняты, вы всё слышите |
| 🚗 **Курьеры и водители** | Новый заказ, адрес, изменение маршрута — глаза на дороге |
| 🏭 **Производство и склад** | Сигналы оборудования, поступление товара, тревоги |
| 🏠 **Умный дом** | Датчики движения, температура, сигнализация — любое событие в голос |
| 💊 **Здоровье** | Напоминания о лекарствах, показания приборов, сигналы мониторов |
| 📦 **Маркетплейсы** | Wildberries, Ozon, Авито — новый заказ или сообщение от покупателя |
| 💬 **Мессенджеры** | Сообщения от конкретных людей или ключевые слова — только нужное |

### Как это работает?

```
Уведомление на телефоне
        ↓
Приложение перехватывает текст
        ↓
Отправляет на облачный сервер
        ↓
Сервер фильтрует через ваш regex
        ↓
Возвращает обработанный текст
        ↓
Телефон озвучивает голосом
```

### Ключевые возможности

- 🎙 **Живой голос** — TTS Piper, женский (Irina) и мужской (Ruslan), работает офлайн
- 🔍 **Гибкая фильтрация** — regex-паттерны: озвучивайте только нужное, в нужном формате
- 📱 **Любые приложения** — Сбербанк, Telegram, WhatsApp, любой маркетплейс — всё что показывает уведомления
- ⚙️ **Несколько устройств** — каждому телефону свой ключ и свои правила обработки
- 🌙 **Тихие часы** — не беспокоит ночью
- 🔋 **Работает в фоне** — оптимизирован для MIUI / HyperOS
- 📂 **Сохранение настроек** — ключ и настройки переживают переустановку приложения

### Требования

- Android 8.0 (API 26) и выше
- ~450 МБ свободного места (голосовые модели)
- Доступ к интернету

### Установка

1. Скачайте последний APK со страницы [Releases](../../releases)
2. Разрешите установку из неизвестных источников
3. При первом запуске выдайте все запрошенные разрешения
4. Введите API-ключ в настройках и нажмите **Сохранить**

> ⚠️ При первом запуске приложение скопирует голосовые модели (~130 МБ) — это займёт 15–30 секунд.

---

## 🇬🇧 English

### What is it?

**NotificationPlayer** is an Android app that intercepts notifications on your phone, processes them through a cloud server, and reads the result aloud using a natural-sounding voice (Piper TTS — Irina / Ruslan).

No screen taps needed. Your phone speaks for itself.

### Who is it for?

| Use case | Scenario |
|----------|----------|
| 💳 **Finance** | Bank transfers, top-ups, instant payments — amount and sender read aloud |
| 🛒 **Business & retail** | New order, payment received, shipment status — hands busy, you hear everything |
| 🚗 **Couriers & drivers** | New job, address, route change — eyes on the road |
| 🏭 **Manufacturing & warehouse** | Equipment alerts, stock arrivals, alarms |
| 🏠 **Smart home** | Motion sensors, temperature, security alerts — any event voiced aloud |
| 💊 **Healthcare** | Medication reminders, device readings, monitor alerts |
| 📦 **Marketplaces** | New order or buyer message — instant audio alert |
| 💬 **Messengers** | Messages from specific contacts or matching keywords — only what matters |

### How it works?

```
Notification appears on phone
        ↓
App intercepts the text
        ↓
Sends it to the cloud server
        ↓
Server filters via your regex pattern
        ↓
Returns processed text
        ↓
Phone reads it aloud
```

### Key features

- 🎙 **Natural voice** — Piper TTS, female (Irina) and male (Ruslan), works offline
- 🔍 **Flexible filtering** — regex patterns: hear only what matters, in the format you want
- 📱 **Any app** — banking apps, Telegram, WhatsApp, any marketplace — anything that sends notifications
- ⚙️ **Multiple devices** — each phone gets its own API key and processing rules
- 🌙 **Quiet hours** — silence during night hours
- 🔋 **Background stable** — optimized for MIUI / HyperOS battery management
- 📂 **Settings survive reinstall** — API key and config stored in Downloads folder

### Requirements

- Android 8.0 (API 26) or higher
- ~450 MB free storage (voice models)
- Internet connection

### Installation

1. Download the latest APK from the [Releases](../../releases) page
2. Allow installation from unknown sources
3. On first launch, grant all requested permissions
4. Enter your API key in Settings and tap **Save**

> ⚠️ On first launch the app will copy voice models (~130 MB) — this takes 15–30 seconds.

---

## 👨‍💻 Author

Developed by **Денис Сочи**  
Telegram: [@your_handle](https://t.me/your_handle)

---

<div align="center">
  <sub>Made with ❤️ for people whose hands are always busy</sub>
</div>
