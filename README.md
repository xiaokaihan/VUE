# VUE
初识VUE

教程： https://www.jianshu.com/p/0c6678671635

1. 安装Node，[https://nodejs.org/en/](https://links.jianshu.com/go?to=https%3A%2F%2Fnodejs.org%2Fen%2F)**Nodejs官网**

2. 查看node版本号和npm版本号

3. 安装淘宝npm镜像（cnpm），为了保证npm安装包的速度

   1. ```bash
      输入命令：npm install -g cnpm --registry=https://registry.npm.taobao.org
      ```

4. 安装vue-cli 脚手架

   1. ```bash
      输入命令：cnpm install --global vue-cli
      ```

   2. 查看cnpm版本号， cnpm --version

   3. cnpm 不是内部命令解决方案， 将cnpm.cmd命令copy一份到npm路径下即可， 或者将cnpm的路径配置到系统环境变量中

5. 查看vue版本，

   1. 输入命令：vue  --version

   2. vue 不是内部命令 解决方案， 将vue.cmd命令的路径配置到系统环境变量中，VUE_HOME=xxxxx，path=%VUE_HOME%

   3. 升级vue版本到3.x

      ```bash
      npm uninstall -g vue-cli
      npm install -g @vue/cli
      ```

6. 创建vue新项目， vue create project _name 

   1. vue create hello-vue

Noted: 由于项目创建完之后生成的node_moudles文件夹过大， 所以上传的项目删除了该目录。 从git下载到本地之后，使用cnpm install 命令可自动下载相关文件。

