# Player 360 Dashboard

Прототип страницы аналитики одного игрока (Player Card) для iGaming CRM.

## Версии

- `player-intelligence-dashboard-full-v16.html` — базовая версия с классами `.metric` и правым выравниванием.
- `player-intelligence-dashboard-full-v20.html` — финальная версия с левым выравниванием метрик (`text-align:left`, `justify-self:start`).
- `index.html` — копия v20 для деплоя на Vercel.

## Локальный запуск

Просто откройте `index.html` в браузере, либо запустите статический сервер:

```bash
python3 -m http.server 8000
```

Затем откройте `http://localhost:8000/`.

## Деплой

Проект развёрнут на Vercel как статический сайт. Обновление — новый пуш в `main`, Vercel автоматически пересобирает.

## Ссылки

- Production (Vercel): https://player360-ochre.vercel.app/
- GitHub: https://github.com/mikhail671/player360
