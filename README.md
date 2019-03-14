# react项目--关于租房系统的建设
### 部署步骤：
+ 安装路由模块
```
cnpm  i  react-router-dom  -S
```
+ 配置项目启动端口，安装cross-env支持跨平台配置端口
```
cnpm  i  cross-env -D
```
 然后通过配置package.json来配置项目启动端口
 ```
 "start": "cross-env PORT=8888 react-scripts start",
 ```
+ 安装semantic-ui-react和semantic-ui-css
```
cnpm  i  semantic-ui-react -S
cnpm  i  semantic-ui-css -S
```
+ 安装axios向后端服务器发送ajax请求
```
cnpm i axios -S
```
+ 安装轮播图库react-image-gallery
```
 cnpm  i  react-image-gallery -S
```
+ 安装react-touch-loader 实现页面下拉刷新，加载更多功能
```
 cnpm  i  react-touch-loader -S
```
+ 安装图片裁剪工具react-avatar-editor
```
 cnpm i  react-avatar-editor -S
```