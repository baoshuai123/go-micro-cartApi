# CartApi api 

在客户端使用 hystrix-go 熔断组件防止服务雪崩,采用了roundrobin 负载均衡轮询算法降低服务器压力,使用用于服务限流的 go 语言库 ratelimit, 该组件基于 Leaky Bucket(漏桶) 实现
