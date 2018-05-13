# Laradock helper (Makefile)

The Makefile with some helpers for laradock

## Installation

Just copy the `Makefile` from this repo to your project root.

You can do this with:

`wget https://raw.githubusercontent.com/KryDos/laradock-helper/master/Makefile`

## Available targets

* `install-laradock` - install laradock, update .env file and set permissions for storage folder (require sudo)

* `up` - run all containers
* `stop` - stop all containers
* `log` - show Laravel log
* `docker-log` - show docker log
* `join-workspace` - get into workspace container
* `join-php` - get into php container
* `join-db` - get into db container and login into postgres
* `npm-install` - install js dependencies
* `build-js` - run npm build
* `build-js-production` - run npm build for production
* `watch-js` - run npm watch
* `key-generate` - generate key for laravel
* `new-migration` - asks you to enter migration name and create it (requires sudo since it created inside a container)
* `run-migrations` - run artisan migrate
* `run-seeds` - run artisan db:seed
* `composer-install` - install php dependencies
* `test` - run test with phpunit
