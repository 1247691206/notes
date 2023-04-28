# flink学习


## flink安装与启动
brew install apache-flink

flink --version

brew info apache-flink

/opt/homebrew/Cellar/apache-flink/1.16.0/libexec/bin/start-cluster.sh

http://localhost:8081/


## flink教程
1. https://nightlies.apache.org/flink/flink-docs-release-1.17/zh/docs/try-flink/datastream/
2. https://github.com/flink-china/flink-training-course



## flink应用开发

mvn archetype:generate \
    -DarchetypeGroupId=org.apache.flink \
    -DarchetypeArtifactId=flink-quickstart-java \
    -DarchetypeVersion=1.6.1 \
    -DgroupId=my-flink-project \
    -DartifactId=my-flink-project \
    -Dversion=0.1 \
    -Dpackage=myflink \
    -DinteractiveMode=false
    


## 参考文献

https://xie.infoq.cn/article/56d2d87d1082977687042034d

http://wuchong.me/blog/2018/11/07/5-minutes-build-first-flink-application/