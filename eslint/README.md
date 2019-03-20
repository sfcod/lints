## Installation

1. Copy packages from package.json and install their newest versions.
2. Copy .eslintrc and .prettierrc into project's folder.
3. Enjoy.

## Usage

```
    "scripts": {
        "flow": "flow",
        "eslint": "eslint --ignore-path .eslintignore --fix --quiet '+(assets)/**/**.{js,jsx}' || exit 0",
        "prettier": "prettier --loglevel=silent --write '+(assets)/**/**.{js,jsx}'"
    }
```
