# Сапфировая гонка

Интерактивная гонка с анимациями, управлением экипажами и проверками D&D. Текущая версия: v22.

## Запуск

Для GitHub Pages выберите Settings → Pages → Deploy from a branch → main → / (root).

Адрес после публикации: https://kitnoone.github.io/saphirrace/

Для локального запуска: `python -m http.server 8000`, затем откройте http://localhost:8000/dist/.

## Содержимое

- `dist/` — сайт и все графические ресурсы.
- `rules/` — правила и пояснения к реализации.
- `tests/` — проверки механик и анимаций; запуск: `node tests/canon-v22.mjs` и остальные файлы `.mjs`.
- `CREW-v18.md` — описание экипажа.

Экспорт текущей версии сайта sapphire-race-engine, исходный коммит 35cd216ea607c7b6d64c37fd8db7265ddd9c6b05.
