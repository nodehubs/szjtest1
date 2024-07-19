
<h1 align="center">next_community_front</h1>

1. 安装依赖

```
cd my-porject
npm install 或 yarn
```

2. 运行项目

```
npm run start
```

## 效果演示

- 前台
  ![image](/screenshot/screenshot1.png)
  ![image](/screenshot/screenshot2.png)
  ![image](/screenshot/screenshot3.png)
- 管理后台
  ![image](/screenshot/demo.gif)

## 技术选型

![image](/screenshot/next_community_front-structure.png)

## 目录结构

```lua
ant-cms-admin
├── api/
│ ├── index.js/         # 接口部分
├── assets/             # less目录
├── components/         # 组件目录
├── constatns/
│ ├── ActionTypes.js/   # redux-sage action-type
│ ├── ConstTypes.js/    # next 页面title 配置
│ └── CustomTheme.js    # 主题样式配置
├── pages               # 主页面
│ ├── _app.js/          # App根组件自定义
│ ├── _document.js/     # document组件自定义
├── redux               # redux目录
├── static              # 静态资源引用目录
├── .editorconfig       # 编辑器配置
├── .eslintrc           # ESlint配置
├── .gitignore          # Git忽略文件配置
├── .prettierignore     # Prettier忽略文件配置
├── .prettierrc         # Prettier配置
├── next.config.js      # next配置
├── pm2.config.js       # pm2配置
├── server              # next服务配置
```

## 功能模块

- [x] 注册
- [x] 登录（持久化）
- [x] 修改密码
- [x] 修改资料
- [x] 发布主题
- [x] 评论主题
- [x] 频道切换
- [x] 点赞
- [x] 响应式布局
- [x] 收藏
- [x] 分享（待开发）
- [x] 积分（待开发）
