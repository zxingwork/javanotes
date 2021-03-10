# javanotes
[toc]
## spring-boot
### 第一个spring-boot程序(by IEDA)
pom.xml添加以下内容：
```xml
    <parent>
        <artifactId>spring-boot-starter-parent</artifactId>
        <groupId>org.springframework.boot</groupId>
        <version>2.3.9.RELEASE</version>
    </parent>
    <dependencies>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
            <version>2.3.9.RELEASE</version>
        </dependency>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-devtools</artifactId>
        </dependency>
    </dependencies>
```
### 热启动
![image](https://user-images.githubusercontent.com/50312187/110588212-ac9a8600-81af-11eb-976b-9caac67e6259.png)

