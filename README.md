# Breadcrumbs Homepage

Made with HTML / Sass Jumpstart

> dart sass powered, includes stylelint and prettier, and autoprefix upon build. develop script includes hot-reload via browsersync.

## Includes Minimal Theme and Components

[**View the documentation >**](https://5t3ph.github.io/html-sass-jumpstart/) available on Github pages, as well as the `index.html` file once you load the project.

## Getting Started

1. Select "Use this template" to copy this project into your own new repo.

2. _Optional:_ Run a find/replace for `tdbc` to update to your preferred prefix (or adjust stylelint settings).

3. You can customize the `theme` Sass directly, or place overrides to variables at the top of the main `style.scss` file before the `theme` file is imported.

4. Then continue with the `develop` script and build something rad :)

## Development Scripts

**`yarn start`**

> Serve with hot reload at localhost:1337

**`yarn run build`**

> Generate minified, autoprefixed CSS for production

Use this as the "Publish command" if needed by hosting such as Netlify.

**`yarn run serve`**

> Serve latest build files at localhost:1337

## Linting

Linting is provided by [Stylelint](https://stylelint.io/) and rules are extended from [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) and [prettier-stylelint](https://github.com/hugomrdias/prettier-stylelint)

### Lint Script

**`yarn run lint`**

> Run stylelint and review errors in terminal

**`yarn run lint:fix`**

> Run stylelint with the fix flag to attempt to resolve found errors
