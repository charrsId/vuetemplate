### Webpack3+vue2+boostrap+server

```
root
|
-- UI 前端目录结构
   |
    -- dist 生成
   |
    -- src 源码
   |
    -- test 测试用例
   |
    -- .editorconfig 编辑器配置
   |
    -- .env 环境配置
   |
    -- .eslintrc es6语法检查
   |
    -- .gitignore git提交忽略配置
   |
    -- .npmrc npm依赖包镜像
   |
    -- package.json npm以来配置及执行命令配置
   |
    -- yarn.lock 自动生成的依赖索引

```
#### 环境要求,若已安装则忽略
```
nodejs v6.x
npm install
```
#### 设置淘宝镜像源
```
yarn config set registry 'https://registry.npm.taobao.org'
```
#### 开发模式
npm start

```
