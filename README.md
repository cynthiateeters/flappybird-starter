# Kaboom Tutorial

This is a simple project template for kaboom.js, a javascript game library.

From [How to make Flappy Bird game in JavaScript - Step by step tutorial](https://www.youtube.com/watch?v=jr-XVRX163I) by [As a Programmer](https://www.youtube.com/@asaprogrammer_)


# Folder structure

- `src` - source code for your kaboom project
- `www` - distribution folder, contains your index.html, built js bundle and static assets


## Development

```sh
$ npm run dev
```

will start a dev server at http://localhost:8000

## Distribution

```sh
$ npm run build
```

will build your js files into `www/main.js`

```sh
$ npm run bundle
```

will build your game and package into a .zip file, you can upload to your server or itch.io / newground etc.