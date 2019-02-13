# Использовано
- [bulma](http://bulma.io/) стили
- [hugo](https://gohugo.io/) для правильного компилирования кода в html
- [netlify](https://netlify.com/) для автоматического деплоя

# Как сделать себе такой же
- взять копию себе ```git clone https://github.com/axel-n/personal_site```
- [скачать hugo](https://gohugo.io/getting-started/quick-start/) (необязательно, если хотите видеть примененные изменения в real time)
    - для локального запуска сервера ```hugo server -D```
- поправить ссылки в data/links.yaml (можно изменять количество)
- поправить дизайн в html файлах
    - если захотите изменять стили. нужно скачать npm пакеты
        - ```npm install```
        - ```npm startnpm```
- поправить код (meta tag) на яндекс метрику в config.toml
- залить изменения в свой github/gitlab
- [netlify](https://netlify.com/)
    1. зарегаться
    2. подлючить репозиторий
    3. настроить собcтвенный домен
    4. указать команду для деплоя ```npm run-script deploy && hugo```

# Возможности для кастомизации
- мультиязычность
- легко добавить блог
- [много чего еще](https://gohugo.io/about/features/)