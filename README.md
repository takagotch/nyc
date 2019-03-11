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
  "": {
    "": "",
    "": ""
  }
}

after_success: npm run coverage

{
  "": {
    "": "",
    "": ""
  }
}

{
  "": {
    "": ""
  }
}

{
  "": {
    "": {
      "": [],
      "": [],
      "": [],
      "": []
    }
  }
}

{
  "nyc": {
    "extends": "@istanbuljs/nyc-config-babel"
  }
}

{
  "": "",
  "": {}
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


