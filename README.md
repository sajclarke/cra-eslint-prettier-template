## Basic Template for CRA setup

This repo is an example template for quickly setting up eslint, prettier and husky with create-react-app

## Notes
- This repo setup was referenced from this [article](https://dev.to/thomlom/how-to-setup-eslint-and-prettier-for-your-react-apps-1n42)
- The lint-staged config was changed from the above referenced article to as follows

```
"lint-staged": {
    "src/**/*.{js,jsx,ts,tsx,json,md}": [
      "prettier --write",
      "eslint --ignore-path .gitignore . --ext ts --ext tsx --ext js --ext jsx"
    ]
  }
```

