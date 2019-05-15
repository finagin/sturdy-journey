[![Software License][ico-license]](LICENSE)

- [Installation](#installation)
  - [Development](#development)
- [License](#license)

## Installation
### Development
- Клонировать репозитарий
- Установить **Php 7.1** ```brew install php71```
- Установить **Composer** ```brew install composer```
- Установить БД:
  - **PostgreSQL** ```brew install postgresql```
  - **MySQL** ```brew install mysql```
- Создать конфиг ```cp .env.exmaple .env```
- Запустить в папке проекта ```composer install```
- Сгенерировать ключ ```php artisan key:generate```
- Настроить ```.env```
- Запустить миграции ```php artisan migrate```
- Установить глобальные зависимости ```npm install -g yarn```
- Установить локальные зависимости проекта ```yarn```
- Собрать фронт ```npm run watch```
- Установить **Valet** ```composer global require laravel/valet```
- Подключить **Valet** ```valet link website```

## License

The MIT License ([MIT](https://opensource.org/licenses/MIT)). Please see [License File](LICENSE) for more information.

<!-- Icons -->

[ico-license]: https://img.shields.io/github/license/mashape/apistatus.svg

