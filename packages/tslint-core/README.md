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
* `prettier` — checks code style with Prettier
* `no-console` — forbids `console.log()`
