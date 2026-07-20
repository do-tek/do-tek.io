# Do-Tek static website

Надёжная статическая версия для GitHub Pages: без сборщика, npm, CDN, PWA и внешних CSS/JS-зависимостей.

## Публикация

Содержимое каталога разместить в корне ветки GitHub Pages.

## Важно

`sw.js` оставлен как self-destruct worker для удаления старой PWA-регистрации и кэшей. Сам сайт service worker не регистрирует.
