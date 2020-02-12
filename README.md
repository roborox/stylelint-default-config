# Roborox Stylelint config

> This config extends stylelint-config-standard

## Installation

### 1. Install npm module

Run following command with terminal

```
npm install stylelint@^11.1.0 @roborox/stylelint-config-default --save-dev
```	

### 2. Applying

To apply this config to your existing eslint configuration just add `@roborox/stylelint-config-default` in
your `.eslintrc.js` file

```
module.exports = {
	extends: ["@roborox/stylelint-config-default"],
	/* your config goes here.. */
}
```
