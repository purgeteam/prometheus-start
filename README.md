# Spring Boot 监控数据可视化(Actuator + Prometheus + Grafana)

![Docker Pulls](https://img.shields.io/docker/pulls/nacos/nacos-server.svg?maxAge=60480)

### 教程链接
- Helm Prometheus Operator 15分钟搞定Kubernetes集群监控
- https://www.jianshu.com/p/973cbbbaab22

- springboot 2.0.x
http://www.itmuch.com/spring-boot/actuator-prometheus-grafana/

- springboot 1.5.x
https://blog.csdn.net/liufei198613/article/details/82460883



### Dashboard市场
https://grafana.com/dashboards?dataSource=prometheus


- ### springboot2.0.x
```xml
<!-- prometheus -->
        <dependency>
            <groupId>io.micrometer</groupId>
            <artifactId>micrometer-registry-prometheus</artifactId>
        </dependency>
        <!-- influx -->
        <dependency>
            <groupId>io.micrometer</groupId>
            <artifactId>micrometer-registry-influx</artifactId>
        </dependency>
        <!-- elastic -->
        <dependency>
            <groupId>io.micrometer</groupId>
            <artifactId>micrometer-registry-elastic</artifactId>
        </dependency>
        <!-- actuator -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-actuator</artifactId>
        </dependency>
```

- ### springboot1.5.x
```xml
<!-- spring-legacy -->
<dependency>
    <groupId>io.micrometer</groupId>
    <artifactId>micrometer-spring-legacy</artifactId>
</dependency>
<!-- prometheus -->
<dependency>
    <groupId>io.micrometer</groupId>
    <artifactId>micrometer-registry-prometheus</artifactId>
</dependency>
<!-- influx -->
<dependency>
    <groupId>io.micrometer</groupId>
    <artifactId>micrometer-registry-influx</artifactId>
</dependency>
<!-- elastic -->
<dependency>
    <groupId>io.micrometer</groupId>
    <artifactId>micrometer-registry-elastic</artifactId>
</dependency>
<!-- actuator -->
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
```