1. 环境  
Debian 12
2. 注意  
如果使用docker desktop on Windows with wsl搭建时，会报422登录错误。触发条件：
   - 使用基于wsl模式的docker desktop
   - external_url中使用http，使用https则不存在此问题
3. 参考  
https://www.cnblogs.com/liugp/p/17324433.html
4. 镜像拉取  
https://dockerproxy.com/