# babel-plugin-transform-remove-import

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
