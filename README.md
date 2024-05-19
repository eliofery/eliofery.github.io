# Jekyll портфолио

Jekyll портфолио

## Команды

Удаление не используемых расширений
```bash
bundle clean --force
```

Обновление расширений
```bash
bundle update <расширение>
```

Указание окружения
```bash
export JEKYLL_ENV=production
export JEKYLL_ENV=development
```

Сборка
```bash
jekyll build
jekyll build --config _config.yml,_config_dev.yml
```

Разработка
```bash
bundle exec jekyll serve --livereload
bundle exec jekyll serve --livereload --config _config.yml,_config_dev.yml
```

Автоматически открытие созданных файлов статей/портфолио в IDE
```bash
export JEKYLL_EDITOR=phpstorm
```

Создание "Портфолио"
```bash
bundle exec jekyll compose "Название работы" --collection "portfolio"
```

Создание "Статьи"
```bash
bundle exec jekyll post "Название страницы"
```

Создание "Страницы"
```bash
bundle exec jekyll page "Название страницы"
```
