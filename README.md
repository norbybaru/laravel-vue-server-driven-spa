# LARAVEL VUE SERVER DRIVEN SPA
## SPA
[View Resources](https://github.com/norbybaru/laravel-vue-server-driven-spa/tree/master/resources/js)
### Directory Structure
```
resouces/
|- js/                  spa source directory
|   |- components/      all components to be imported into your views
|   |- lang/            ldirectory contains ocalization files. 
|   |- layouts/         directory contains application layouts
|   |- middleware/      directory contains application middleware that should run before rending pages or layout
|   |- pages/           directory contains application views
|   |- plugins/         directory contains js plugins to import
|   |- routers/         directory contains applications routing
|   |- store/           directorty contains Vuex store files for state management
|   |- app.js           javascript file serve as entry point for your application
```
## Features

- Laravel 7
- Vue + VueRouter + Vuex + VueI18n + ESlint
- Pages with dynamic import and custom layouts
- Login, register, email verification and password reset
- Authentication with JWT
- Socialite integration
- Bootstrap 4 + Font Awesome 5

## Installation

- Clone project. `git clone git@github.com:norbybaru/laravel-vue-server-driven-spa.git`
- Edit `.env` and set your database connection details
- (When installed via git clone or download, run `php artisan key:generate` and `php artisan jwt:secret`)
- `php artisan migrate`
- `npm install`

## Usage

#### Development

```bash
# build and watch
npm run watch

# serve with hot reloading
npm run hot
```

#### Production

```bash
npm run production
```
