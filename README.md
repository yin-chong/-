＃ 奇舞周刊
每天坚持阅读奇舞周刊

```
Serverless
 根据CNCF的定义，Serverless是指构建和运行不需要服务器管理的运行服务的概念
 Serverless = FaaS + BaaS。
 FaaS（Function as a Service） 就是一些运行函数的平台，比如阿里云的函数计算、AWS 的 Lambda 等
 BaaS（Backend as a Service）则是一些后端云服务，比如云数据库、对象存储、消息队列等。利用 BaaS，可以极大简化我们的应用开发难度。
Serverless的主要特点：
 事件驱动
  函数在 FaaS 平台中，需要通过一系列的事件来驱动函数执行。
 无状态
  因为每次函数执行，可能使用的都是不同的容器，无法进行内存或数据共享。如果要共享数据，则只能通过第三方服务，比如 Redis 等。
 无运维
  使用 Serverless 我们不需要关心服务器，不需要关心运维。这也是 Serverless 思想的核心。
 低成本
  使用 Serverless 成本很低，因为我们只需要为每次函数的运行付费。函数不运行，则不花钱，也不会浪费服务器资源
 BFF：服务于前端的后端
 
 视频背景透明的方法：
  将视频背景色设置为黑色，同时设置如下css：
  video{
     mix-blend-mode：screen;
  }
  该方法在所有不需要兼容IE浏览器的项目中都可以使用
                                                                                                            
  ```

