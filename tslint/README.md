## Installation

1. Copy packages from package.json and install their newest versions.
2. Copy .tslintrc and .prettierrc into project's folder.
3. Enjoy.

## Usage

```
    "scripts": {
        "tslint": "tslint --fix --quiet '+(assets)/**/**.{ts,tsx}' || exit 0",
        "prettier": "prettier --loglevel=silent --write '+(assets)/**/**.{ts,tsx}'"
    }
```
