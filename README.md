# CartApi api 

在客户端使用 hystrix-go 熔断中间件防止服务雪崩,采用了roundrobin 负载均衡轮询算法降低服务器压力,加入了漏桶算法限流
