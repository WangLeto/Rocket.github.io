# 前端JavaScript文档
## 在线文档
请访问我们的 [JavaScript文档页](https://wangleto.github.io/RocketJavaScript.github.io/)  
由于 [gitpages的静态html文件仅支持引入https协议的脚本文件](https://stackoverflow.com/questions/38931964/script-stops-working-when-hosted-on-github-pages)，这份在线文档的渲染出了一些问题。如果感觉影响阅读，请使用本地生成文档的方法。

## 本地生成文档
- 安装yuidocjs  

  ```bash
  npm install -g yuidocjs
  ```
  
- 生成文档
  
  ```bash
  yuidoc .
  ```
生成文件在根目录下的 ```out``` 文件夹中，打开 ```index.html``` 以查看