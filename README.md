### nyc
---
https://github.com/istanbuljs/nyc

```js
class Yarsay {
  constructor (msg = "maybe if we ask nicely, they';; just give us their riffiwobbles!"
    var joe = fs.readFileSync(path.resove(__dirname, '../joe.txt'), 'utf-8'))
    
    var batman = (sad) => {
      console.log(`hello world`)
    }
    
    joe = joe.replace(/ /g, '_')
}
```

```
nyc --extension .jsx --extension .mjs npm test
npm i nyc --save-dev
npm i nyc -g
nyc npm test
nyc --reporter=lcov --reporter-text-lcov npm test

nyc check-coverage --lines 95 --functions 95 --branches 95
nyc --check-coverage --lines 100 npm test
nyc check-coverage --lines 95 --per-file
nyc report
nyc report --reporter=lcov
nyc report --reporter=<custom-reporter-name>

npm install coveralls nyc --save-dev

npm install codecov nyc --save-dev
```

```
after_success: npm run coverage

{
  "scripts": {
    "test": "nyc tap ./test/*.js",
    "coverage": "nyc report --reporter=text-lcov > coverage.lcov && codecov"
  }
}

after_success: npm run coverage

{
  "scripts": {
    "test": "nyc mocha",
    "coverage": "nyc report --reporter=text-lcov | coveralls"
  }
}

{
  "nyc": {
    "igonore-class-method": "render"
  }
}

{
  "nyc": {
    "watermarks": {
      "lines": [80, 95],
      "functions": [80, 95],
      "branches": [80, 95],
      "statements": [80, 95]
    }
  }
}

{
  "nyc": {
    "extends": "@istanbuljs/nyc-config-babel"
  }
}

{
  "description": "These are just examples for demonstration, nothing prescriptive",
  "nyc": {
    "check-coverage": true,
    "per-file": true,
    "line-file": 99,
    "lines": 99,
    "statements": 99,
    "functiohns": 99,
    "branches": 99,
    "include": [
      "src/**/*.js"
    ],
    "exclude": [
      "src/**/*.spec.js"
    ],
    "ignore-class-method": "methodToIgnore",
    "reporter": [
      "lcov",
      "text-summary"
    ],
    "require": [
      "./test/helpers/some-helper.js"
    ],
    "extension": [
      ".jsx"
    ],
    "cache": true,
    "all": true,
    "temp-dir": "./alternative-tmp",
    "report-dir": "./alternative"
  }
}

{
  "nyc": {
    "all": true,
    "include": [
      "src/**/*.js"
    ],
    "exclude": [
      "**/*.spec.js"
    ]
  }
}

[
  'coverage/**',
  'packages/*/test/**',
  'test/**',
  'test{,-*}.js',
  '**/*{.,-}test.js',
  '**/__tests__/**',
  '**/node_modules/**',
  '**/babel.config.js',
]

{
  "nyc": {
    "extension": [
      ".jsx",
      ".mjs"
    ]
  }
}

{
  "nyc": {
    "require": [
      "@babel/register"
    ],
    "sourceMap": false,
    "instrument": false
  },
  "scripts": {
    "test": "cross-env NODE_ENV=test nyc mocha"
  }
}

{
  "babel": {
    "presets": ["@babel/preset-env"],
    "env": {
      "test": {
        "plugins": ["istanbul"]
      }
    }
  }
}

{
  "scripts": {
    "test": "nyc mocha"
  }
}
```


