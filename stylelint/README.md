## Installation

1. Copy packages from package.json and install their newest versions.
2. Copy .stylelintrc into project's folder.
3. Enjoy.

## Usage

```
    "scripts": {
        "stylelint": "stylelint --fix --quiet '+(assets)/**/**.{css,scss}' || exit 0"
    }
```
