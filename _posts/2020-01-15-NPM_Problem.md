#NPM问题

使用npm过程中遇到的一些问题总结：



---

###1. Package.json中的模块依赖

####（1）package有两种依赖：

* dependencies —— 运行依赖，依赖的项该是正常运行该包时所需要的依赖项；

* devDependencies —— 开发依赖，开发的时候需要的依赖项，像一些进行单元测试之类的包。

####（2）常用两种情况：

* package.json不存在时：运行命令: npm init可自动创建package.json文件；

* package.json存在时：运行命令: npm install 或者 npm install –save-dev会自动将package.json中的模块安装到node-modules文件夹下。



---

###2. 控制Node版本

* nvm ls

* nvm install 8.5







