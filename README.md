# Adverts-on-react-build
## Запуск
* Установить Node.js

https://nodejs.org/en/

* Скачать папку build с репозитория
* В терминале установить локальный сервер командой:
>     npm install -g serve
* Открыть терминал в родительском каталоге по отношению к папке build (каталог, в котором находится build)
* Запустить сервер командой:
>     serve -s build 

Описание:

https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#deployment

---
## Останов
* В терминале, где запущен сервер, нажать сочетание **CTRL + C**
* Подтвердить останов сервера

Если процесс не остановился:
* в браузере перейдите на страницы по ардесам:

<chrome://serviceworker-internals>

<chrome://appcache-internals>

* Найдите процессы localhost:5000
* Завершите оба процесса

Решение найдено на странице:

https://github.com/react-boilerplate/react-boilerplate/issues/373