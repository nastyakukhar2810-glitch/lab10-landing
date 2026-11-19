# UkrMovych — лендинг (ЛР №10)

Лендинг тренажера української мови **UkrMovych** («+1 бал на НМТ за 20 секунд щодня») з інтегрованими динамічними медіакомпонентами.

## JS-бібліотеки (через CDN, Vanilla JS)

| Бібліотека | Де використано | Налаштування |
|---|---|---|
| Swiper.js v11 | слайдер відгуків (6 слайдів): автоплей, стрілки, пагінація, брейкпоінти 1/2/3 слайди | `assets/js/plugins.js` |
| Fancybox v5 | галерея з 6 екранів тренажера (єдиний альбом `data-fancybox`), ефект fade, зум | `assets/js/plugins.js` |
| Typed.js | ефект друку тексту в Hero-секції | `assets/js/plugins.js` |

Стилі плагінів підключені в `<head>`, скрипти — перед `</body>`, ініціалізація обгорнута в `DOMContentLoaded`.

## Технології

HTML5, Tailwind CSS (CDN), `custom-styles.css`, Font Awesome, Google Fonts (Inter), Git, GitHub, Vercel/Netlify.

## Структура

```
lab10-landing/
├── index.html
├── custom-styles.css
├── assets/
│   ├── images/    hero.png, logo.png
│   ├── icons/     icon-*.png
│   ├── gallery/   шість екранів тренажера (+ thumbs/ — мініатюри)
│   └── js/        plugins.js (ЛР №10), validation.js (ЛР №9)
└── README.md
```

## Запуск локально

Відкрити папку у VS Code → Live Server → `index.html`.

## Демо

- GitHub: _посилання на репозиторій_
- Live Demo: _посилання Vercel / Netlify_
