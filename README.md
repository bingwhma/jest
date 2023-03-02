# jest 
npm install jest --save-dev

# modify package.json file

  "scripts": {  
      "test": "jest"  
    },  
    "jest": {  
      "collectCoverage": true  
    },  

# Using Babel

npm install @babel/core @babel/preset-env --save-dev  
npm install --save-dev babel-jest @babel/core @babel/preset-env

.babelrc  
  {  
      "presets": ["@babel/preset-env"],  
      "targets": {  
        "node": "current"  
      }  
  } 
  
or
babel.config.js  
module.exports = {  
  presets: [['@babel/preset-env', {targets: {node: 'current'}}]],  
};  
