# Overview

`jackinthebox` is a frontend project scaffolding tool to get web development quickly up and running. Out fo the box it has:

- [`pug`](https://pugjs.org/api/getting-started.html) HTML templating.
- [`sass`](https://sass-lang.com/) CSS styling.
- [`normalize-scss`](https://github.com/JohnAlbin/normalize-scss) for consistent browser standards.
- [`turbo-scss`](https://github.com/lyutkin/turbo-scss) set of CSS utility classes.
- [`webpack`](https://webpack.js.org/) for JS modules.
- [`jest`](https://facebook.github.io/jest/) for JS testing.
- [`imagemin`](https://github.com/imagemin/imagemin) for images optimization.
- [`faker`](https://github.com/marak/Faker.js/) to pull off some random simple content.

# Getting started
- Clone the repository and install all dependencies via npm:
```
git clone https://github.com/lyutkin/jackinthebox.git
cd jackinthebox
npm install && npm start
```

- Commands:
	- `npm start` to start web server with hot reloading.
	- `npm test` to run tests.
	- `npm run prod` to make a production build with files minification and optimization.
	- `npm run zip` to make a `.zip` archive of `dist` folder.
