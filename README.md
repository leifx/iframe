iframe 跨域通信


分别到两个test文件下面 执行 node http.js

得到端口不同
http://localhost:8080
http://localhost:8000


test1/index.html  主页面
test2/flexible.html 子页面

使用postMessage发送信息

接收信息
window.addEventListener("message", receiveMessage, false);

结合文档 https://developer.mozilla.org/zh-CN/docs/Web/API/Window/postMessage


