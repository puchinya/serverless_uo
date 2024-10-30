
# About this

This is fork version of serverless 3.

I am adding only new AWS Lambda runtime support.

# Install
1. add '.npmrc' to same directory as 'package.json'.  
  .npmrc content is following.
```
@puchinya:registry=https://npm.pkg.github.com
```
2. install @puchinya/serverless_uo.
```
npm install --save-dev @puchinya/serverless_uo
```
3. add package.json script.
```
"scripts": {
  "serverless": "serverless"
}
```
4. run serverless.
```
npm run serverless
```
