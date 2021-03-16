## npm tutorial

- ```mkdir npm-helloworld```
- ```cd npm-helloworld/```
- ```npm init```
```
{
  "name": "npm-helloworld",
  "version": "1.0.0",
  "description": "This is hello world!",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Yuki Agatsuma",
  "license": "ISC",
  "repository": {
    "type": "git",
    "url": "git+ssh://git@github.com/yukiaga/npm-hello-world.git"
  },
  "keywords": [
    "npm",
    "npm-hello-world"
  ],
  "bugs": {
    "url": "https://github.com/yukiaga/npm-hello-world/issues"
  },
  "homepage": "https://github.com/yukiaga/npm-hello-world#readme"
}
```
- ```git init```
- ```touch README.md```
- ```git add README.md```
- ```git commit -m "first commit"```
- ```git branch -M main```
- ```git remote add origin git@github.com:yukiaga/npm-hello-world.git```
- ```git push -u origin main```
- ```npm adduser```
- ```npm login```
- ```npm whoami```
- ```npm version```
- ```npm publish```

## how to use
- https://github.com/yukiaga/npm-package-using-test

## to do
- https://qiita.com/ARR/items/ff1bbf663426b5eb7293#%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%8B%E3%83%B3%E3%82%B0%E3%81%AB%E9%96%A2%E3%81%97%E3%81%A6
- 中規模開発用にCJ, ESM, min.jsのだし分けを行いたい

