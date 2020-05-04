# nexus3-maven-import
批量导入本地jar包到nexus3

### 使用方法
1.  选择要上传的仓库，并记录仓库URL
如：`http://localhost:8081/repository/maven_repo/`
2.  将脚本拷贝到本地jar所在的目录
3.  运行命令
```shell
sh mavenImport.sh -u 用户名 -p 密码 -r http://localhost:8081/repository/maven_repo/
```
4. 检查jar是否完全导入

### 备注
1. 如果需要上传snapshots包到仓库，需设置仓库为**Mixed**
