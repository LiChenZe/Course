> # 博学之, 审问之, 慎思之, 明辨之, 笃行之;  
> # 壹、贰、叁、肆、伍、陆、柒、捌、玖、拾;


> ### 壹.创建第一个应用

        1.引入 required 模块：我们可以使用 require 指令来载入 Node.js 模块。

        2.创建服务器：服务器可以监听客户端的请求，类似于 Apache 、Nginx 等 HTTP 服务器。

        3.接收请求与响应请求 服务器很容易创建，客户端可以使用浏览器或终端发送 HTTP 请求，服务器接收请求后返回响应数据。




>   ***分析Node.js 的 HTTP 服务器：***
        
        - 第一行请求（require）Node.js 自带的 http 模块，并且把它赋值给 http 变量。
        - 接下来我们调用 http 模块提供的函数： createServer 。这个函数会返回 一个对象，
            这个对象有一个叫做 listen 的方法，这个方法有一个数值参数， 指定这个 HTTP 服务器监听的端口号。
        
    











> ### 贰.创建第一个应用