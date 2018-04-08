# spring-boot-config-client
config读取文件

config-service：http://localhost:8888

git文件如：spring-boot-config-file

git中文件修改push完毕后，需要调用config-client项目：post http://localhost:8091/refresh
此时客户端配置才会生效

<dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-actuator</artifactId>
        </dependency>

