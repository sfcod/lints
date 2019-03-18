## Installation

1. Copy packages from package.json and install their newest versions.
2. Copy .eslintrc and .prettierrc into project's folder.
3. Enjoy.

## Usage

```
    "scripts": {
        "flow": "./node_modules/.bin/flow",
        "eslint": "./node_modules/.bin/eslint --fix --quiet '+(assets)/**/**.js?(x)' || exit 0"
    }
```
