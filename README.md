# eslint-config-chuion

This package provides Chuion's base JS .eslintrc as an extensible shared config.

## Usage

### eslint-config-chuion

Our default export contains all of our ESLint rules, including ECMAScript 6.

First, install this package
```sh
npm install --save-dev eslint-config-chuion eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "chuion"
}
```

### eslint-config-chuion/legacy

For some legacy project using es5.

First, install this package
```sh
npm install --save-dev eslint-config-chuion eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "chuion/legacy"
}
```

### eslint-config-chuion/react
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-chuion eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
Then add following contents to your .eslintrc file
```
{
  "extends": "chuion/react"
}
```

## License
MIT
