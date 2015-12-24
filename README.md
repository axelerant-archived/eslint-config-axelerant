# eslint-config-axelerant

[![Build Status](https://semaphoreci.com/api/v1/projects/cf24f068-9b02-4859-b37c-ee6aab50d0d9/644930/badge.svg)](https://semaphoreci.com/skippednote/eslint-config-axelerant)
[![npm version](https://badge.fury.io/js/eslint-config-axelerant.svg)](http://badge.fury.io/js/eslint-config-axelerant)

This package provides Axelerant's .eslintrc as an extensible shared config.

## Usage

* Install `eslint-config-axelerant` with additional required dependencies.

```
npm install --save-dev eslint babel-eslint eslint-config-axelerant
```

* Create a `.eslintrc` in the root of your project.

* Add the following snippet to the `.eslintrc`
```json
{
  "extends": "axelerant"
}
```
