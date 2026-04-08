# local-rp-lore.ru

Страница адаптирована для публикации через **GitHub Pages**.

## Что уже настроено

- Автодеплой в GitHub Pages через GitHub Actions (`.github/workflows/deploy-pages.yml`).
- Отключение Jekyll (`.nojekyll`), чтобы статические файлы публиковались как есть.
- Все пути к ассетам в `index.html` относительные, поэтому сайт корректно открывается как на корневом домене, так и на `https://<user>.github.io/<repo>/`.

## Как включить публикацию

1. В репозитории откройте **Settings → Pages**.
2. В разделе **Build and deployment** выберите **Source: GitHub Actions**.
3. Пушьте изменения в ветку `main` — workflow автоматически развернёт сайт.
