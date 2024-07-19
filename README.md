## szjtest1

hobot-react-antd-ts-template

### 文件说明

```
Antares Android
├── webpack                 // webpack 配置文件
│   ├── env.js              // 环境配置
│   ├── webpack.base.config.js
│   ├── webpack.dev.config.js
│   └── webpack.prod.config.js
├── scripts                 // 部署及其他脚本
│   ├── build.sh
│   └── deploy.sh
├── docs                    // 文档
├── src                     // 业务代码
│   ├── assets              // 静态资源
│   │   └── images          // 图片
│   ├── components          // 公共组件
│   │   ├── Bread           // 面包屑导航
│   │   ├── HeaderBar       // 顶栏
│   │   └── SideMenu        // 侧边栏导航
│   ├── config              // 配置目录
│   │   ├── constants.ts    // 常量定义
│   │   └── errors.ts       // 错误码配置
│   ├── mock                // mock配置
│   │   └── index.ts
│   ├── models              // 数据模型
│   │   └── index.ts
│   ├── modules             // 业务模块
│   │   ├── Main
│   │   └── Account
│   ├── navigator           // 导航
│   │   └── index.ts        // 导航配置
│   ├── routers             // 路由
│   │   └── config.ts       // 路由配置
│   ├── schemas             // 业务类型定义
│   ├── services            // 数据服务层
│   │   ├── request.ts      // 网络请求封装
│   │   └── index.ts
│   ├── styles
│   │   ├── global.less     // 全局样式
│   │   └── variables.less  // 样式变量
│   ├── types               // 申明文件
│   ├── utils               // 工具
│   │   └── helpers.ts      // 工具函数
│   ├── App.tsx
│   ├── store.ts
│   ├── index.html
│   └── index.tsx
├── README.md
├── package-lock.json
└── package.json
```

### 技术栈

- 框架：`react`
- 路由：`react-router-dom`
- 数据管理：`rematch`
- 界面：`antd`
- 网络库：`axios`
- 按需加载：`@loadable/component`
- 热更新：`react-hot-loader`
- 单元测试：`enzyme`, `jest`
- 代码格式统一：`Prettier`
- TypeScript 规范：[tslint](tslint.json)
- Less 规范：[stylelint](.stylelintrc.js)
- pre-commit
  - 调用 TSLint 对不规范的代码进行自动 fix
  - 调用 stylelint 对不规范的样式进行自动 fix
  - 调用 commitlint 对 commit message 进行规范检查
