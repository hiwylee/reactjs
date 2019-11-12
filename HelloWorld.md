# HelloWorld 예제
(*) proxy setting
```
npm config set proxy http://proxyserver:proxyport
npm config set https-proxy http://proxyserver:proxyport
npm config set strict-ssl false npm config set registry "http://registry.npmjs.org/"
npm --without-ssl --insecure install
```
#### 아래 실형 결과 direct도 path에 포함 할 것 
yarn global bin

```
yarn config set proxy http://proxyserver:proxyport
yarn config set https-proxy http://proxyserver:proxyport
yarn config set strict-ssl false
```

## 1. 프로젝트 생성

'''
yarn create react-app hello-world
cd hello-world
'''
'''
yarn start
yarn run v1.19.1
$ react-scripts start
Starting the development server...
Compiled successfully!

You can now view hello-world in the browser.

  Local:            http://localhost:3000/
  On Your Network:  http://10.179.90.8:3000/

Note that the development build is not optimized.
To create a production build, use yarn build.
'''
