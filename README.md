# Laravel 5, Angular 2 Stub Project

This is a Stub Project for Laravel 5 / Angular 2 Development. 

This project is meant only as a starting point for your Angular2 masterpiece.  

### Setup For Development

```
$ git clone https://github.com/chris-cmsoft/laravel5-angular2-stub.git
$ cd laravel5-angular2-stub/
$ rm -rf .git/
$ composer install
$ npm install
$ git init
$ git remote add origin ***YOUR_REPO_URL***
$ git add .
$ git commit -m "initial laravel angular setup"
$ git push origin master
```
### Typescript

Typescript is kept in resources/assets/typescript.

When compiled the Javascript files end up in public/app.

To compile typescript and watch for changes
```sh
$ gulp typescript && gulp watch-typescript
```
### Angular
If any additional packages are needed ( specialised routers etc. ):

1) Add them to package.json under devDependencies
2) Run :
    ````sh
    $ npm install
    ````
3) Add Them to the gulpfile copy string

### Testing

```sh
$ phpunit
```
##### Jasmin testing has not yet been added.

## License

This laravel5-angular2-stub Project is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
