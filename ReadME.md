## README
> springcloud-test

*   [1、说明](#introduce) 
*   [2、资料](#document) 

> [github]( https://github.com/scott180/springcloud-test ) &ensp;  [dillinger]( https://dillinger.io/ )  &ensp;  [作业部落]( https://www.zybuluo.com/mdeditor )   



<h2 id="introduce"></h2>

### 1、说明
> <b> Spring Cloud为开发人员提供了快速构建分布式系统中一些常见模式的工具（例如配置管理，服务发现，断路器，智能路由，微代理，控制总线）。</b> 分布式系统的协调导致了样板模式, 使用Spring Cloud开发人员可以快速地支持实现这些模式的服务和应用程序。他们将在任何分布式环境中运行良好，包括开发人员自己的笔记本电脑，裸机数据中心，以及Cloud Foundry等托管平台。
Spring Cloud 采用了英国伦敦地铁站的名称来命名，并由地铁站名称字母A-Z依次类推的形式来发布迭代版本。 &ensp; 
[版本说明]( https://mp.weixin.qq.com/s/IqlHFsIrFJ5vBG9-1gldJw )  &ensp; [官方文档](https://www.springcloud.cc/spring-cloud-dalston.html )

-------

> - Eureka 用于服务的注册于发现；
> - Feign 支持服务的调用以及均衡负载；
> - Hystrix 处理服务的熔断防止故障扩散；
> - Spring Cloud Config 服务集群配置中心;
> - Zuul 供动态路由，监控，弹性，安全等的边缘服务。Zuul是Netflix出品的一个基于JVM路由和服务端的负载均衡器;
> - Spring Cloud Sleuth 和 Zipkin 进行分布式链路跟踪,快读定位服务故障点;



<h2 id="document"></h2>

### 2、资料

>纯洁的微笑 &ensp; [ityouknow]( http://www.ityouknow.com/spring-cloud.html ) &ensp;[cnblogs]( https://www.cnblogs.com/ityouknow/category/994104.html ) &ensp; [github]( https://github.com/ityouknow/spring-boot-examples )

- [springcloud(一)：大话Spring Cloud]( https://www.cnblogs.com/ityouknow/p/6791221.html )
- [springcloud(二)：注册中心Eureka]( https://www.cnblogs.com/ityouknow/p/6854805.html )
- [springcloud(三)：服务提供与调用]( https://www.cnblogs.com/ityouknow/p/6859802.html )
- [springcloud(四)：熔断器Hystrix]( https://www.cnblogs.com/ityouknow/p/6868833.html )
- [springcloud(五)：熔断监控Hystrix Dashboard和Turbine]( https://www.cnblogs.com/ityouknow/p/6889059.html )

- [springcloud(六)：配置中心git示例]( https://www.cnblogs.com/ityouknow/p/6892584.html )
- [springcloud(七)：配置中心svn示例和refresh]( https://www.cnblogs.com/ityouknow/p/6906917.html )
- [springcloud(八)：配置中心服务化和高可用]( https://www.cnblogs.com/ityouknow/p/6922705.html )
- [springcloud(九)：配置中心和消息总线（配置中心终结版）]( https://www.cnblogs.com/ityouknow/p/6931958.html )
- [springcloud(十)：服务网关zuul]( https://www.cnblogs.com/ityouknow/p/6944096.html )  

- [springcloud(十一)：服务网关Zuul高级篇](http://www.ityouknow.com/springcloud/2018/01/20/spring-cloud-zuul.html )  
- [springcloud(十二)：使用Spring Cloud Sleuth和Zipkin进行分布式链路跟踪](http://www.ityouknow.com/springcloud/2018/02/02/spring-cloud-sleuth-zipkin.html )  
- [springcloud(十三)：Spring Cloud Consul 使用详解](http://www.ityouknow.com/springcloud/2018/07/20/spring-cloud-consul.html )  
- [Springcloud(十四)：Spring Cloud 开源软件都有哪些？](http://www.ityouknow.com/springcloud/2018/08/06/spring-cloud-open-source.html )  
- [springcloud(十五)：服务网关 Spring Cloud GateWay 初级篇](http://www.ityouknow.com/springcloud/2018/12/12/spring-cloud-gateway-start.html )  
- [springcloud(十六)：服务网关 Spring Cloud GateWay 服务化和过滤器](http://www.ityouknow.com/springcloud/2019/01/19/spring-cloud-gateway-service.html )   
- [springcloud(十七)：服务网关 Spring Cloud GateWay 熔断、限流、重试](http://www.ityouknow.com/springcloud/2019/01/26/spring-cloud-gateway-limit.html )  

```
 命令执行
 java -jar spring-cloud-eureka-0.0.1-SNAPSHOT.jar --spring.profiles.active=peer1
 
 端口被占用
 netstat -ano|findstr 8001
 tskill pid

```
-------
>方志朋博客 &ensp;[csdn]( https://blog.csdn.net/forezp/article/details/70148833 ) &ensp;[fangzhipeng]( https://www.fangzhipeng.com/spring-cloud.html ) &ensp;[github]( https://github.com/forezp/SpringCloudLearning )
