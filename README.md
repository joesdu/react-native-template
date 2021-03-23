# Yarn2.x 包管理工具

必须安装 Yarn 1.x 才行,使用方法,解压到项目根目录即可使用.

## Getting Started

本项目由于项目中使用 yarn 2.x 进行包管理,所以建议大家使用[yarn 下载](https://classic.yarnpkg.com/latest.msi).npm 不能保证正常使用.[yarn 2.x 官网](https://yarnpkg.com/)

更新依赖包

```bash
yarn upgrade-interactive
```

更新 yarn

```bash
yarn set version berry
```

导入 yarn 更新依赖包插件

```bash
yarn plugin import interactive-tools
```

导入 yarn TypeScript 库自动加入插件

```bash
yarn plugin import typescript
```

更新 React Native 版本

```bash
npx react-native upgrade
```
