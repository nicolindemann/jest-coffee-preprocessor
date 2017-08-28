# jest-coffee-preprocessor

[![Greenkeeper badge](https://badges.greenkeeper.io/nicolindemann/jest-coffee-preprocessor.svg)](https://greenkeeper.io/)
Simple Coffee Script Preprocessor for Jest

# Example Installation:


In package.json:

```json
  "jest" :{
    "transform": {
      "^.+\\.jsx?$": "<rootDir>/node_modules/babel-jest",
      "^.+\\.coffee$": "<rootDir>/node_modules/jest-coffee-preprocessor/index.js"
    },
    "moduleFileExtensions": [
      "coffee",
      "js",
      "json",
      "jsx"
    ]
  }
```
