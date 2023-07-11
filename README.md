1. 创建名字为 xxx-spring-boot-starter 的启动器项目
2. 创建名字为 xxx-spring-boot-autoconfigure的项目
    * 编写属性绑定类 xxxProperties.
    * 编写服务类，引入 xxxProperties.
    * 编写自动配置类XXXAutoConfiguration注入配置。
    * 创建 spring.factories 文件，用于指定要自动配置的类。

* 启动器项目为空项目,用来引入xxx-spring-boot-autoconfigure等其他依赖
* 项目引入starter,配置需要配置的信息
