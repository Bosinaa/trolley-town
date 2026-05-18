# trolley.town — публикация на itch.io

## Что загружать

Загрузи **один файл** `index.html` из корня этой ветки (`itch-io`) в виде ZIP-архива.

```
trolley-town.zip
└── index.html
```

## Настройки на itch.io

| Поле | Значение |
|------|----------|
| Kind of project | HTML |
| Viewport dimensions | 760 × 900 (или Fluid) |
| Mobile friendly | ✓ включить |
| Fullscreen button | ✓ включить |
| Shared array buffer | не нужен |

## Перед публикацией

1. **Замени ссылки доната** в `index.html` — найди `YOUR_USERNAME` (3 места):
   - Telegram: `https://t.me/YOUR_USERNAME`
   - Boosty: `https://boosty.to/YOUR_USERNAME`
   - Ko-fi: `https://ko-fi.com/YOUR_USERNAME`
   - Buy Me a Coffee: `https://buymeacoffee.com/YOUR_USERNAME`

2. **Обложка** — загрузи Cover image 630×500 px (itch.io рекомендует именно этот размер).

3. **Screenshots** — сделай 2–3 скриншота (экран с дилеммой + экран результатов).

## Описание для страницы (можно скопировать)

> 21 моральная дилемма — вагонетки, биоэтика, ИИ, справедливость. Правильных ответов не существует.
> Твои выборы строят карту по 5 этическим осям и находят твой нравственный архетип среди героев кино, книг и истории.
>
> Короткий режим: ~3 мин · Полный: ~8 мин

## Теги для itch.io

`quiz` `philosophy` `moral` `ethics` `russian` `singleplayer` `browser` `interactive-fiction`

## Что отличает эту ветку от `main`

- `index.html` лежит в корне (не в `src/`) — itch.io требует этого
- Добавлены `<meta viewport>`, og-теги, twitter-карточка
- AdSense отключён (не работает в iframe itch.io)
- Мобильный CSS для экранов < 600px
- Фикс открытия внешних ссылок поверх iframe
