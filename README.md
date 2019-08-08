## 🍜 introduction

This is a react template(or called starter) for typescript users, details below:

- use `babel` for `typescript` compile
- use `jest` and `@testing-library/react` for test
- use [this repo](https://github.com/XHMM/my-config-files) for lint setup
- and includes these libraries:
  - `styled-components` and related babel plugin
  - `@material-ui/core`, `@material-ui/styles`
  - `@material-ui/icons` and babel setup for reducing bundle size
  - `react-router-dom`
- support `sass`

## 🥡 install

Option one (automatically):

1. use corresponding **[CLI](https://github.com/XHMM/trs)** to conveniently fetch and extract this starter.
2. then `cd folder` and run `npm install`

Option two (manually):

1. download this repo and extract it.
2. then `cd folder` and run `npm install`

## 🍱 scripts

- `npm run dev` to start webpack-dev-server

- `npm run build` to build

- `npm run test` for test

- `npm run eslint:fix` to automatically fix every fixable problems

## 🥗notes

- use alias to import files, current there are four alias available:

  ```js
  import Img from '@images/apple.jpg';
  import Button from '@components/Button';
  import useCounter from '@hooks/useCounter';
  import Index from '@pages/index/Index';
  ```

  

