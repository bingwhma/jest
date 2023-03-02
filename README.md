# jest 
npm install jest --save-dev

# modify package.json file

  "scripts": {  
      "test": "jest"  
    },  
    "jest": {  
      "collectCoverage": true  
    },  

# ES support for jtest
## babel
npm install @babel/core @babel/preset-env --save-dev

.babelrc  
  {  
      "presets": ["@babel/preset-env"],  
      "targets": {  
        "node": "current"  
      }  
  }  
