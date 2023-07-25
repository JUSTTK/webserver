# webserver
#· 项目简介：在 Linux 上实现高并发的 Web 服务器，能够通过网页完成用户的登录、注册。
#· 应用技术：利用线程池、非阻塞 Socket、Epoll、模拟 Proactor 事件处理模式实现并发模型；
           #利用有限状态机实现 HTTP 报文的解析和应答，可以解析 POST、GET 请求；
           #利用 MySQL 记录用户数据，实现用户的登录、注册；实现了同步、异步日志记录。
#· 成果：经 WebBench 测试可以达到上万的并发连接数。
