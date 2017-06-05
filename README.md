# eslint-config-biddster

Container for the various eslint configs I have (and will have).

# Installation

    $ cd your-project
    $ npm install eslint eslint-config-biddster --save-dev

# Configuration

Add this to your package.json:

```json
"eslintConfig": {
    "env": {
      "es6": true,
      "node": true,
      "mocha": true
    },
    "parserOptions": {
      "ecmaVersion": 6,
      "sourceType": "module"
    },
    "extends": "eslint-config-biddster/es6-node"
  }
```