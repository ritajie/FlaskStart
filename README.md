经常用flask来快速开发web应用，索性写了一个脚手架，把自己喜欢的bootstrap和jquery也弄好～
脚手架里用到了这些东西：
**.
|____index.py** (只写了个根目录的路由)
**|____static
| |____css
| | |____bootstrap.min.css
| | |____bootstrap-theme.css
| |____js
| | |____jquery.min.js
| | |____bootstrap.min.js
| | |____jquery.cookie.js
| |____img
| | |____deer.jpg
|____templates
| |____index.html** (“继承”base.html，放上一张🦒的照片hhh)
**| |____base.html** (作为jinja2的模板文件，除了引用static静态文件之外没干任何事)
