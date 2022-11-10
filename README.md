# mini-vue
拥有自己的 mini Vue

## 环境配置
- `npm install` 安装依赖
- `/src` 实现模块
    - `/tests` 测试模块
- `index.js` 待测试代码
- `babel.config.js` Babel 配置
- `tsconfig.json` TS 配置
- 移步分支 2

## reactive
- proxy 代理
- get 
    - track 依赖收集
- set 
    - trigger 触发依赖

## effect
- fn.run() 触发 get 收集依赖
