# proxy_master
简化代理设置
* 设置当前所在项目的代理，设置全局代理
  * 实现简单的proxy设置工具 happy proxy：hp -npm -g http[ http://127.0.0.1[ alias local]]  //全局版
  * 实现简单的proxy设置工具 happy proxy：hp -npm http   //恢复成上一个代理或者取消代理
  * 实现简单的proxy设置工具 happy proxy：hp -npm http -d  //取消代理
  * 实现简单的proxy设置工具 happy proxy：hp -npm all -d   //取消所有代理
  * 资源：hp.cmd 命令行 --- 通过npm i构建和设置cmd访问功能
  * 参照：electron的实现
  * 路线
  * 用nodejs简单实现通过node调用设置当前代理的功能，使用当前环境而不是复制
  * 思考如何建立架构
  * 思考如何获取环境参数
  * 思考如何实现help文本
  * 思考如何设置环境状态
  * 思考如何通过cmd调用到nodejs文件
  * 思考如何部署cmd文件和将nodejs文件安装到系统目录
  * 思考如何生成cmd文件
  * 如何安装nodejs文件
  * 如何确保全局cmd文件的调用能力