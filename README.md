# Mestia Hotel Level website

# Добавление новой информации
1. Клонировать репозиторий. Ветка main
2. Отредактировать страницы (папки content, data).
3. Закомитить изменения.

# Локальная проверка
1. hugo server --disableFastRender

# Локальная сборка сайта
Обычно не нужна
1. hugo --minify

## Необходимые программы
1. [Hugo](https://gohugo.io/installation/)

# Развертывание на сервере
Развертывание и обновление происходит автоматически. Для этого настроен скрипт в github actions. 
Сайт хостится на сайте github.io. Т.е. содержимое репозитория (main): https://github.com/malkhazpaliani/malkhazpaliani.github.io опубликовано в https://malkhazpaliani.github.io 

### Скрипт публикации
https://github.com/malkhazpaliani/mestiahotellevel/blob/main/.github/workflows/main.yml

# Разработчик
https://github.com/dontsovcmc
