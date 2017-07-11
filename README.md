1.构建Resource Manager Docker，执行如下命令：

```bash
./gradlew -P dockerTag=username/myriad buildRMDocker
docker push username/myriad
```

这将从源代码构建RM，保存并push image *username/myriad*.


2.rm.json文件是在Marathon环境中启动Myriad docker的启动脚本
