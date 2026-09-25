# Рассвет — квиз «Какое у тебя осеннее утро?»

Мини-приложение для Telegram и MAX: квиз из 5 вопросов, 4 типа результата с советами и переход к световому будильнику на Wildberries.

## Что менять
Всё в блоке `CONFIG` в начале `<script>` в `index.html`:
- `brand` — название бренда
- `productName` — название товара
- `wbUrl` — ссылка на карточку WB
- `ozonUrl` — ссылка на Ozon
- `price` — цена (или `""`, чтобы скрыть)
- `botUsername` — имя бота без @ (для кнопки «поделиться»)
- `maxBotLink` — ссылка на бота в MAX (для кнопки «поделиться» внутри MAX)
- `features` — 4 характеристики товара

Вопросы — в `QUESTIONS`, тексты результатов — в `RESULTS`.

## Публикация
Settings → Pages → Source: Deploy from a branch → `main` / root → Save.
Ссылка: https://tanyalapkhan-commits.github.io/rassvet-quiz/

## Telegram и MAX
Один файл работает в обоих мессенджерах: приложение само определяет, где открыто.
- **Telegram:** @BotFather → бот → Menu Button или `/newapp` → вставить ссылку на страницу.
- **MAX:** business.max.ru → Чат-боты → бот → Настройки → вставить ссылку на страницу и выбрать кнопку запуска.
