参考来源
http://blog.fens.me/nodejs-express4/

npm install                                         # 下载依赖库
npm start                                           # 启动服务器

npm install supervisor -g

supervisor ./bin/www  #自动监控目录及长启动


实际启动值 ：node ./bin/www




CND加速
http://www.bootcdn.cn/

EJS 模板
http://blog.csdn.net/zhangxin09/article/details/18409119


node_modules, 存放所有的项目依赖库。
package.json，项目依赖配置及开发者信息
app.js，程序启动文件
public，静态文件(css,js,img)
routes，路由文件(MVC中的C,controller)
Views，页面文件(Ejs模板)