nredis-proxy 是一个以redis 协议为主的高性能稳定的代理中间件服务，不侵入业务代码，与业务毫无联系，不需要改任何应用代码。
主要有以下功能：
     
     1：自带连接池，性能高效
     
     2：提供分片策略，扩展性强，可自定义分片算法
     
     3：提供读写分离，一主多从
     
     4：提供自动监听功能，主挂了，提供选举算法，从作为主
     