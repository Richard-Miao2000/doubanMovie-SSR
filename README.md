# 豆瓣电影服务端渲染
技术基础 Vue 2.0 + vue-router + vuex + element-ui + nodejs 服务端渲染
线上演示环境 贴一下浏览器渲染的地址吧，项目新鲜出炉 还没来得及部署到云服务器上
和浏览器端渲染对比 <a href='https://github.com/monkeyWangs/doubanMovie'> 浏览器端doubanMovie</a>
## 简单的看下gif：注意地址栏跟浏览器端渲染带 #/ 不一样。而是对应得 /
<img width="600" alt="screen shot 2016-08-11 at 6 06 57 pm" src="https://github.com/monkeyWangs/doubanMovie-SSR/blob/master/public/doubanSSR.gif">

## Features

- 服务器端
  - Vue + vue-router + vuex working together
  - Server-side data pre-fetching
  - Client-side state & DOM hydration
  - Automatically inlines CSS used by rendered components only
- vue 单文件组件
  - Hot-reload in development
  - CSS extraction for production
- Real-time List Updates with FLIP Animation

## 简单概要
<img width="973" alt="screen shot 2016-08-11 at 6 06 57 pm" src="https://cloud.githubusercontent.com/assets/499550/17607895/786a415a-5fee-11e6-9c11-45a2cfdf085c.png">

## 构建步骤
**Requires Node.js 6+**

``` bash
# install dependencies
npm install # or yarn

# serve in dev mode, with hot reload at localhost:8080
npm run dev

# build for production
npm run build

# serve in production mode
npm start
```
