# Publications

Структура папки:

```
Publications/
├── index.html                  ← главная страница (не трогать руками)
├── robots.txt                  ← запрет индексации
├── update_publications.md      ← скрипт для Cursor
├── README.md                   ← этот файл
└── books/
    ├── learnbook-ai-models.html
    ├── multi-agent-tutorial.html
    └── ... новые книги сюда
```

## Как добавить новую книгу

1. Положи .html файл в папку `books/`
2. Открой Cursor в этой папке
3. Напиши: `запусти update_publications.md`
4. Готово — книга появится в index.html, стиль выровняется автоматически

## Как задеплоить

```bash
git add .
git commit -m "add new book"
git push
```
