# HomePage-Vue

一个使用 Vue 3 + TypeScript + Vite 构建的现代化个人主页，有参与项目展示、技能栈、联系我等功能。

## 特性

- 🚀 使用 Vue 3 + TypeScript + Vite 构建
- 🎨 支持两岸主题切换
- 📱 响应式设计，支持移动端
- ⚡️ 快速加载和页面切换
- 🔍 SEO 友好
- 📦 组件自动导入
- 🎯 TypeScript 类型安全
- 🔧 可配置的主题

## 技术栈

- Vue 3
- TypeScript
- Vite
- Vue Router
- TailwindCSS
- PostCSS
- ESLint + Prettier
- Husky + lint-staged

## 开发

```bash
# 克隆项目
git clone https://github.com/dcyyd/vue.git

# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm build

# 预览生产构建
npm preview

# 代码格式化
npm format

# 代码检查
npm lint
```

## 项目结构

```
homepage-vue
├── api/		# 项目用到的API
├── node_modules	# 项目依赖包
├── public/             # 静态资源目录，存放无需处理的文件
├── src/
│   ├── assets/         # 项目资源，如图片、字体等
│   ├── components/     # 组件目录，包含可复用的 Vue 组件
│   ├── config/         # 配置文件目录，存放项目的配置信息
│   ├── layouts/        # 布局组件，定义页面的整体结构
│   ├── pages/          # 页面组件，对应不同的路由页面
│   ├── router/         # 路由配置，定义页面的路由规则
│   ├── styles/         # 样式文件，包含全局样式与组件样式
│   ├── types/          # TypeScript 类型定义，增强代码的类型安全
│   ├── utils/          # 工具函数目录，包含常用的工具方法
│   ├── App.vue         # 根组件，作为整个应用的入口
│   └── main.ts         # 入口文件，初始化 Vue 应用
├── .env                # 环境变量文件，配置项目的环境参数
├── index.html          # HTML 模板文件，作为应用的基础模板
├── package.json        # 项目配置文件，记录项目依赖与脚本命令
├── tsconfig.json       # TypeScript 配置文件，定义 TypeScript 编译选项
├── vite.config.ts      # Vite 配置文件，定制 Vite 的构建与开发选项
└── README.md           # 项目说明文档，提供项目的详细信息
```

## 部署

项目可以部署到任何静态网站托管服务：

```bash
# 构建项目
npm run build

# 部署 dist 目录
```

## 许可证

[MIT](./LICENSE)
