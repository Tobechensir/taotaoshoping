
第一个springboot_web项目
用springinit初始化之后
1.添加依赖设置热部署
 <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-devtools</artifactId>
            <optional>true</optional> <!-- 这个需要为 true 热部署才有效 -->
        </dependency>

2.使用mybatis逆向工程只需要
    1.在pom文件中添加mybatis和mysql驱动的依赖

    2.在pom文件中添加mybatis逆向工程的依赖
    3.在applicaton.yml文件中配置数据库的基本参数
    4.在resources文件中新建一个generatorConfig.xml文件（用于生成逆向工程的xml文件）
2.1建议单独对逆向工程做个项目。

