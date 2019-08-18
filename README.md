"electron-builder" Typescript Webpack Hello World Demo
=======================================================

之前webpack把代码输出到`dist`，发现`webpack-builder`打包时出报错：

```
Error: Application entry file "build/main.bundle.js"
in the "/Users/freewind/workspace/electron-builder--typescript-webpack-package-mac-demo/dist/mac/electron-builder--typescript-webpack-package-mac-demo.app/Contents/Resources/app.asar"
does not exist. Seems like a wrong configuration.
```

经测试发现不能是`dist/build`等目录，必须是别的名字，所以在这个demo中我使用`bundled`。
应该有可以配置的地方，但是还没找到。

```
npm install
npm demo
```
