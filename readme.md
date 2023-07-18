# 将web应用打包成桌面应用，基于nodejs

## 说明
打包脚本 fork [ZhugeXican/electron](https://github.com/ZhugeXican/electron)，
打包环境是哪个平台（Mac，Windows，Linux），默认就是根据环境来生成的，在 Mac 环境打包 Windows 应用会出现未知错误，已经提 [issue](https://github.com/ZhugeXican/electron/issues/16)，在 Windows 打包是可以的。
electron-packager . test --arch=x64 --platform=win32 --out=./out --asar --app-version=0.0.1 --overwrite --ignore=node_modules

## 操作步骤
1. 安装必要的环境，如：node
2. 将你的项目文件拷贝到 project 目录中
3. 安装依赖 `npm install`
4. 开发环境调试：`npm run dev`
5. 打包：`npm run start`
6. 成功会输出在了out文件夹

## 深入学习 
[electron官网](https://electronjs.org/docs)
