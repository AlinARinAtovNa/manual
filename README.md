# Docs as Code

Документация проекта, собранная с помощью MkDocs.

**Сайт:** https://AlinARinAtovNa.github.io/manual/

## О проекте

Этот проект демонстрирует подход "документация как код", где:

- Документация пишется в Markdown.
- Хранится в Git (контроль версий).
- Собирается в статический сайт с помощью MkDocs.
- Публикуется на GitHub Pages.

## Локальный запуск

`pip install mkdocs mkdocs-material`
`python -m mkdocs serve`

## Сборка статического сайта

`python -m mkdocs build`

Собранный сайт появится в папке site/.

## Публикация на GitHub Pages

`python -m mkdocs gh-deploy --clean`