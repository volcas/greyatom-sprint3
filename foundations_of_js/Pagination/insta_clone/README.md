# Instagram Clone

A lightweight foundation for your next webpack based frontend project.

### Installation

```
npm install
```

### Start Dev Server

Enter this command to start your project and building the UI.

```
npm start
```

### Build Prod Version

Run this command to see how the site might look and load in the production environment. After running this command, a build folder would be created. You can double click the `index.html` file in the build folder to see your production site.

```
npm run build
```

### Features:

- ES6 Support via [babel](https://babeljs.io/) (v7)
- SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
- Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `npm run build`, [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) is used to move the css to a separate file. The css file gets included in the head of the `index.html`.
