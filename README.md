# 配置 webpack5-React18+TS 开发打包环境及其优化

项目内所示目录结构和文件

```yaml
|---public
|       favicon.ico 
|       index.html # html模板
|       
+---src
|   |   App.tsx
|   |   images.d.ts 
|   |   index.tsx # 入口文件
|   |   style.css 
|   |   style.less
|   |   
|   +---assets
|   |   \---imgs
|   |           22kb.webp
|   |           5kb.webp
|   |           
|   \---components
|           Class.tsx # 装饰器测试
|           index.ts # ES6+语法测试
|           LazyDemo.tsx # 懒加载测试
|           PreFetchDemo.tsx # 资源预加载
|           PreloadDemo.tsx # 资源预加载
|           
+---webpack
|       paths.js # 常用公共路径
|       proxy.js # 前端代理解决跨域
|       rules.js # 模块处理规则
|       webpack.base.js # 公共配置
|       webpack.dev.js # 开发环境配置
|       webpack.prod.js # 打包环境配置
|       webpack.speed.js # webpack构建分析配置
|       
|   .browserslistrc # 浏览器兼容清单
|   .env
|   .eslintignore
|   .eslintrc.json # eslintrc配置
|   .gitignore
|   babel.config.js # babel配置
|   package.json
|   postcss.config.js # postcss配置
|   README.md
|   tailwind.config.js # tailwind配置
|   tsconfig.json # ts配置
```

1. 安装依赖

```bash
pnpm i
```
```bash
npm i
```

2. 开发环境运行

```bash
pnpm dev
```
```bash
npm run dev
```

3. 生产环境打包

```bash
pnpm build
```
```bash
npm run build
```

4. webpack打包分析
   
```bash
pnpm speed
```
```bash
npm run speed
```

各文件中都有详细注释

webpack各项配置说明和插件功能都有相关注释，可以按照自己的需要进行修改，也可以直接使用完全ok！
