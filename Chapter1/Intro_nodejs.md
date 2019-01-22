# Section 2 Introduction to Node.js

## Create Node.js app

* 引入 required 模块

  ```javascript
  var http = require(“http");
  ```



* 创建服务器

  ``` javascript
  http.createServer(function (request, response){
    response.writeHead(200, {'Content-Type': 'text/plain'});
    response.end("Hello World!\n');
   }).listen(8888);
   
   console.log('Server running at http://127.0.0.1:8888/');
  ```

  

  

  