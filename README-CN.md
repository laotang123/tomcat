# 快速启动

* idea 添加一个application
* 设置vm options参数
    ```shell
    -Dcatalina.home=catalina-home
    -Dcatalina.base=catalina-home
    -Djava.endorsed.dirs=catalina-home/endorsed
    -Djava.io.tmpdir=catalina-home/temp
    -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
    -Djava.util.logging.config.file=catalina-home/conf/logging.properties
    -Duser.country=EN
    ```
* 成功启动 http://127.0.0.1:8080/
