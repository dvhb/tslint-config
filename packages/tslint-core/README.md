# TSLint Config DVHB

> Basic [TSLint config](https://palantir.github.io/tslint/usage/configuration/) for DVHB projects

## Installation

```sh
npm install @dvhb/tslint-config --save-dev
```
## Usage

In `tslint.json`:

```json
{
  "extends": "@dvhb/tslint-config"
}
```
## Extends

* [tslint-config-airbnb](https://github.com/progre/tslint-config-airbnb) — rules based on [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
* [tslint-config-prettier](https://github.com/prettier/tslint-config-prettier) — disables all rules that may cause conflicts with [prettier](https://prettier.io/)
* [tslint-plugin-prettier](https://github.com/prettier/tslint-plugin-prettier) — runs Prettier as a TSLint rule

## Rules
* `no-console` — forbids `console.log()`
* `prettier` — checks code style with Prettier
* `variable-name` — restrict variables names to camelCase
  - `allow-pascal-case` — for classes, constructors and react components name
  - `allow-leading-underscore` — for `noUnusedParameters` TS rule when required parameter of function is not first
