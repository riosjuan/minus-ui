# minus-ui

Minimal UI framework

## Run project

```
npm run serve
```

If the project is going to be run for the first time, install dependencies:

```
npm install
```

### Sass linting

In order to avoid CSS bad practices, make use of the sass linting utility. This project uses the [Airbnb CSS / Sass Styleguide](https://github.com/airbnb/css). To run the linter use:

```
npm run sass:lint
```
#### Example of linter warning

```
assets/scss/style/_colors.scss
  15:3  warning  Color 'grey' should be written in its hexadecimal form #808080  no-color-keywords

✖ 1 problem (0 errors, 1 warning)
```
