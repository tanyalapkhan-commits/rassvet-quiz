# Рассвет — квиз «Какое у тебя осеннее утро?»

Telegram-мини-приложение: квиз из 5 вопросов, 4 типа результата с советами и переход к световому будильнику на Wildberries.

## Что менять
Всё в блоке `CONFIG` в начале `<script>` в `index.html`:
- `brand` — название бренда
- `productName` — название товара
- `wbUrl` — ссылка на карточку WB
- `ozonUrl` — ссылка на Ozon
- `price` — цена (или `""`, чтобы скрыть)
- `botUsername` — имя бота без @ (для кнопки «поделиться»)
- `features` — 4 характеристики товара

Вопросы — в `QUESTIONS`, тексты результатов — в `RESULTS`.

## Публикация
Settings → Pages → Source: Deploy from a branch → `main` / root → Save.
Ссылка: https://tanyalapkhan-commits.github.io/rassvet-quiz/
