# 目录结构说明
- app 路径下为electron相关代码，包含electron和基于express启动的本地服务
- client 路径下为前端代码，在这里，按照模块化划分，每个功能都是一个module，如目前有login模块，模块之间最好不要有依赖关系。

# 待完成
- app 路径下配置文件【基于配置，区别开发/生产环境】
- app 路径下server进一步完善
- 开发环境下前端代码热更新，没有自动刷新浏览器
- 打包配置完善
  - 目前打包配置还没有完善，还差基础配置的补充，linux、mac、windows打包配置的完善