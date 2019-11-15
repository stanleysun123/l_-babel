

***
npm init -y
npm install --save-dev babel-cli
***

add plugins into babelrc 

***
{
  "plugins": ["@babel/plugin-transform-arrow-functions"]
}
***

run as below 

***
npx babel script.js
npx babel script1.js
***

env preset
The env preset is very nice: you tell it which environments you want to support, and it does everything for you, supporting all modern JavaScript features.

E.g. “support the last 2 versions of every browser, but for Safari let’s support all versions since Safari 7`



