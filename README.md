运行 node server.js 8888 可以成功监听 8888 端口
访问 http://localhost:8888 得到一个 HTML 页面，页面里面有一个 h1 标签，并且页面会请求一个 style.css
style.css 内容为 h1{color: red}
访问其他未知路径一律提示「你访问的页面不存在」，并且状态码为 404
