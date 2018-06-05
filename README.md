# babel-plugin-transform-remove-import

[![Greenkeeper badge](https://badges.greenkeeper.io/dleitee/babel-plugin-transform-remove-import.svg)](https://greenkeeper.io/)

This plugin removes all `import` calls.

## Example

**In**

```javascript
import strman from 'strman'
```

**Out**

```javascript
```

## Installation

```sh
npm install babel-plugin-transform-remove-import
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["transform-remove-import"]
}
```

### Via CLI

```sh
babel --plugins transform-remove-import script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["transform-remove-import"]
});
```
