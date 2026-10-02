# Organic Landing

Адаптивная вёрстка лендинга по макету. Проект построен на семантическом HTML, методологии БЭМ и SCSS без использования фреймворков.

**Демо:** https://Az212At.github.io/organic-landing/

## Технологии

- HTML5 (семантические теги: `header`, `nav`, `main`, `section`, `article`, `aside`, `address`, `footer`)
- SCSS (партиалы, переменные, `@use`)
- БЭМ
- Адаптивная вёрстка (media queries)
- Git

## Особенности

- Структура разбита на независимые блоки по БЭМ: `the-header`, `nav`, `header-content`, `the-main`, `the-footer`, `footer-column`
- Стили разделены на партиалы по компонентам, общие цвета вынесены в переменные
- Адаптация под экраны шириной до 768px

## Структура проекта

```
organic-landing/
├── index.html
├── package.json
├── assets/
├── public/
├── css/
│   └── style.css
└── src/
    └── scss/
        ├── index.scss
        ├── main.scss
        ├── normalize.scss
        ├── _variables.scss
        ├── theme/
        └── components/
            ├── _header.scss
            ├── _main-section.scss
            ├── _footer.scss
            └── _footer-column.scss
```
