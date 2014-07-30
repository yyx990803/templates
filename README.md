Personal templates to be used with [new](https://github.com/yyx990803/new).

## Tempaltes

### Sketch

Simple Browserify-based setup with separate stylus file. Requires `watchify` and `stylus` to be globally installed.

#### Usage

``` bash
$ new sketch
$ npm run dev
```

### App

Browserify-based setup that structures the project into individual components that can include templates, stylus files and javascript files. Templates and styles are inlined via `partialify` and `stylify` and css is inserted with `insert-css`. Everything is bundled into one, single built javascript file.

#### Usage

``` bash
$ new app
$ npm install
$ npm run dev
```