# Тестовый проект лендинга для практики верстки

## Перед стартом проекта необходимо

* Убедиться, что установлены node.js и npm. Для этого достаточно написать в Терминале
> node -v

Если видно версию, тогда все хорошо

> npm -v

Если видно версию, тогда все хорошо

* Убедиться, что установлен gulp 4 версии, т.к. если будет меньше - работать не будет.
Если не установлен - тогда ставим:

> npm install gulpjs/gulp-cli#4.0 -g

* Если не ставится, тогда:

# Uninstall previous Gulp installation and related packages, if any
> npm rm gulp -g
> npm rm gulp-cli -g
> cd [your-project-dir/]
> npm rm gulp --save-dev
> npm rm gulp --save
> npm rm gulp --save-optional
> npm cache clean

# Install the latest Gulp CLI tools globally
> npm install gulpjs/gulp-cli -g

# Install Gulp 4 into your project from 4.0 GitHub branch as dev dependency
> npm install gulpjs/gulp#4.0 --save-dev

# Check the versions installed. Make sure your versions are not lower than shown.
> gulp -v
---
[10:48:35] CLI version 1.2.2
[10:48:35] Local version 4.0.0-alpha.2

## Инструкция для старта проекта
* Сканировать данный репозиторий
> git clone https://github.com/Irritable/landing.git

* Запустить команду npm install в терминале. Данная команда установит все пакеты, которые были указаны в файле
packege.json, а также все их зависимости"# landing"