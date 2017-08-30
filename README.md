## git 基本操作


* git  add .  把项目修改添加到缓存区
* git   commit 将本次修改成一个版本
* git  diff  未添加到git缓存区之前详细修改信息
* ctrl z  退出
* git    log  查看当前版本信息
* git  log --prett=oneline   参数可以把版本信息显示到一行
* git  reset --hard  【版本号】回退到该版本
* git  init 将本地的文件夹变成仓库
*

*******************

##   nvm 安装 node
*  npm  是node的包
* 安装 nvm
* curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash
* 执行上边的命令就可以安装 nvm 了。

* 安装 node
* 查看有哪些版本可以安装
* nvm ls-remote
* 安装版本 v5.10.1
* nvm install v5.10.1
* 这样就安装好了 node ，同时 npm 页就装好了。执行下面的命令来检查下本地的 node ，npm 版本吧。

* node -v
* npm -v
* 如果是 windows 机器的话，直接到 node 官网下载对应版本的软件，双击安装即可。

设置默认 node 版本
利用 nvm 可以在我们的机器上安装多个版本 node ，并且可以进行灵活的切换。下面将 5.10.1 这个 node 版本设置为默认。执行下面语句即可。重启 shell 之后，执行 node -v 可以查看当前的 node 版本。

nvm alias default 5.10.1
配置 npm
npm 是一个非常强大的包管理工具，可以让我们非常方便的安装、卸载、更新插件包，但是默认的 npm 下载包是从国外的服务器获取，速度很不给力，这里推荐使用淘宝镜像。

到淘宝相关页面。可以看到有多种使用方式。这里推荐执行下面的命令，即使用淘宝定制的 cnpm 。

npm install -g cnpm --registry=https://registry.npm.taobao.org
好，之后我们就可以用 cnpm 这个命令了。

检查下装好了吗
cnpm -v
之后装包的话可以直接
cnpm install gulp

*******************************
