# typescirpt--relyon

//全局安装typescript
npm install -g typescript
//查看typescript版本
tsc -v
//跟新typescript的版本
npm update -g typescript

//安装Tpyings
typings 主要是用来获取.d.ts文件。当typescript使用一个外部JavaScript库时,会需要这个文件，当然好多的编译器都用它来增加智能感知能力。
npm install -g typings

//安装 node 的 .d.ts 库
typings install dt~node –global

//创建ts_demo项目
创建ts_demo目录
在命令行cmd下进入ts_demo目录
cd ts_demo
输入：npm init，创建package.json

//创建 tsconfig.json
