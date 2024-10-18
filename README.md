# catclub 项目
**猫友会,你可以分享你的猫猫照片**

## 微服务框架
- **Spring Boot**
  - 用于快速构建独立、生产级别的 Spring 应用，简化开发和配置。
  - SpringBoot:2.7.17
  - SpringCloud:
  - <dependency>
        <groupId>org.springframework.cloud</groupId>
        <artifactId>spring-cloud-starter</artifactId>
        <version>2021.0.8</version> <!-- 使用具体的版本号 -->
    </dependency>

## 微服务框架Spring Cloud Alibaba

负责微服务之间的调用：

<dependency>   

​         <groupId>com.alibaba.cloud</groupId>

​        <artifactId>spring-cloud-alibaba-dependencies</artifactId>

​      <version>2021.0.4.0</version>

</dependency>



## 服务注册与发现

- **Nacos**
  - 提供服务的注册和发现功能，使微服务能够动态互相调用负载均衡和服务配置。

## 网关服务
- **Spring Cloud Gateway**
  - 作为 API 网关，负责路由请求和处理服务之间的通信。

## 服务调用
- **Spring Cloud OpenFeign**
  - 声明式的服务调用客户端，简化 RESTful 接口的调用。

## 监控服务
- **Prometheus + Grafana**
  - Prometheus 用于数据监控，Grafana 用于数据可视化，监控系统健康状态和性能。

## 日志管理
- **ELK Stack**
  - **Elasticsearch**：用于存储和检索日志数据。
  - **Logstash**：用于收集、处理和转发日志数据。
  - **Kibana**：用于可视化日志数据，提供查询和分析功能。

## 分布式追踪
- **Zipkin**
  - 提供微服务间的调用链追踪，帮助分析性能瓶颈和错误。

## 安全服务
- **Spring Security + OAuth2 + JWT**
  - 提供认证和授权机制，确保 API 的安全性。

## 消息传递
- **Kafka**
  - 用于处理高吞吐量的消息传递，支持异步通信和事件驱动架构。

## API管理
- **Swagger**
  - 自动生成 API 文档，方便前后端的协作和接口测试。

## 持续集成/持续部署
- **Jenkins**
  - 实现自动化构建、测试和部署，提高开发效率。

## 容器化
- **Docker**
  - 将应用及其依赖打包为容器，确保环境一致性。

## 容器编排
- **Kubernetes**
  - 管理和编排容器，提供自动扩缩、负载均衡和服务发现等功能。

## 数据库
- **MySQL**
  - 关系型数据库，适合存储结构化数据。

## 缓存
- **Redis**
  - 高性能的内存数据库，提供数据缓存，提升应用性能。

## 测试工具
- **JUnit**
  - 进行单元测试，确保代码质量和功能正确性。
