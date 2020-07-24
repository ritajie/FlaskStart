脚手架的目录结构：

```
.
|____index.py (只写了个根目录的路由)
|____templates
| |____index.html (“继承”base.html，放上一张🦒的照片hhh)
| |____base.html (作为jinja2的模板文件，除了引用static静态文件之外没干任何事)
|____static
| |____css
| | |____bootstrap.min.css
| | |____bootstrap-theme.css
| |____js
| | |____jquery.min.js
| | |____bootstrap.min.js
| | |____jquery.cookie.js
| |____img
| | |____deer.jpg
```
