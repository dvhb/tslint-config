# TSLint Config DVHB for React

> A [TSLint config](https://palantir.github.io/tslint/usage/configuration/) for React and React Native [DVHB](https://dvhb.com) projects

### Installation
```sh
npm install @dvhb/tslint-config-react --save-dev
```
### Usage
   
In `tslint.json`:

```json
{
  "extends": "@dvhb/tslint-config-react"
}
```

## Extends

* [@dvhb/tslint-config](https://github.com/dvhb/tslint-config/tree/master/packages/tslint-core) — basic rules for DVHB projects
* [tslint-react](https://github.com/palantir/tslint-react/) — default rules for React by [TSLint](https://palantir.github.io/tslint/) team

## Rules Overwrite
* `jsx-boolean-value` — forbids value for truthy props
