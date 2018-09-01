
# parcel-vue
基于 Parcel 的零配置 Vue 开发模板
## 目录结构
```
├── dist                构建结果
│   └── index.html
├── index.html          首页文件
├── node_modules
├── package.json
├── postcss.config.js   CSS配置
├── src                 开发源码
│   ├── App.vue
│   ├── assets
│   ├── components
│   ├── main.js
│   └── router
└── static              静态文件
    ├── css
    ├── img
    └── js

```

## 已知问题
.postcssrc 文件 添加以下配置，首页样式失效：
```
"modules": true
```

## 使用
```bash

# 运行
npm run dev

# 编译
npm run build
```