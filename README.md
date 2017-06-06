# REM CSS

通过 CSS 实现 REM 适配。

**PS: 从 1.7.0 后开始支持。**

## 修改说明

- 设置配置项 `enableREM` 为 `false`
- 添加 postcssPlugins

  ```
  require('postcss-plugin-px2rem')({
    rootValue: 750 / 20
  })
  ```
- 新增样式文件 `./src/css/rem.scss`

## 开始

```bash
# 安装依赖
npm install # 或者使用 yarn install

# 开发模式
npm start

# 构建
npm run build
```
