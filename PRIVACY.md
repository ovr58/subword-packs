# SubWord — Privacy Policy / Политика приватности

## Русский

Дата вступления в силу: 2026-11-16.

### Что не собирается

SubWord не собирает персональные данные и ничего не отправляет разработчику. У расширения нет аккаунта, нет телеметрии и нет аналитики. История просмотра (идентификаторы видео в закладках) не покидает браузер.

### Что хранится только в вашем браузере

В хранилище браузера (IndexedDB и `storage`) лежат: настройки, установленные языковые пакеты, закладки и локальный журнал событий. Журнал уходит разработчику только файлом, который вы выгрузили сами. Всё это удаляется при удалении расширения.

### Когда расширение ходит в сеть

- Страницы `youtube.com`: расширение работает на них и читает субтитры видео, чтобы показать карточку слова.
- Языковые пакеты скачиваются с `github.com` и `*.githubusercontent.com` (релизы репозитория данных `subword-packs`).
- Онлайн-голос: когда в браузере нет локального голоса, текст слова уходит в службу озвучки самого браузера.

Других сетевых запросов расширение не делает.

### Права из манифеста — зачем

- `storage` — хранить настройки, пакеты, закладки и журнал в браузере.
- `unlimitedStorage` — хранить крупные языковые пакеты без лимита квоты.
- `offscreen` — (Chrome и Edge) скрытый документ для перевода и озвучки.
- `*://*.youtube.com/*` — работать на страницах YouTube: читать субтитры и показывать карточку слова.
- `https://github.com/*` — скачивать языковые пакеты.
- `https://*.githubusercontent.com/*` — скачивать файлы пакетов с хоста релизов GitHub.

## English

Effective date: 2026-11-16.

### What is not collected

SubWord does not collect personal data and sends nothing to the developer. The extension has no account, no telemetry and no analytics. Watch history (video IDs in bookmarks) never leaves the browser.

### What is stored only in your browser

Browser storage (IndexedDB and `storage`) holds: settings, installed language packs, bookmarks and a local event log. The log reaches the developer only as a file that you exported yourself. All of it is removed when you uninstall the extension.

### When the extension uses the network

- `youtube.com` pages: the extension runs on them and reads the video subtitles to show the word card.
- Language packs are downloaded from `github.com` and `*.githubusercontent.com` (releases of the `subword-packs` data repository).
- Online voice: when the browser has no local voice, the word text goes to the browser's own speech service.

The extension makes no other network requests.

### Manifest permissions — why

- `storage` — keep settings, packs, bookmarks and the log in the browser.
- `unlimitedStorage` — keep large language packs without a quota limit.
- `offscreen` — (Chrome and Edge) a hidden document for translation and speech.
- `*://*.youtube.com/*` — run on YouTube pages: read subtitles and show the word card.
- `https://github.com/*` — download language packs.
- `https://*.githubusercontent.com/*` — download pack files from the GitHub release host.
