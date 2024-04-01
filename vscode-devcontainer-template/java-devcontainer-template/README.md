# 我希望获得一个用于开发springboot的基础环境

这个模板提供一个基础的开发容器，里面包含：

1. git
* 解释：git将读取你本地的git config中的用户名和邮箱，用作开发容器的提交。同时，安装 `redjue.git-commit-plugin` 拓展用于提供git提交模板。

2. java
* 解释：本模板默认安装java17，并安装vscode中的java扩展(`vscjava.vscode-java-pack`)和springboot扩展(`vmware.vscode-boot-dev-pack`)

3. maven
* 解释：本模板默认根据java特性中安装latest版本maven。

# 该怎么使用提供的开发容器模板

将 `.devcontainer文件夹` 复制到项目的根目录下即可。同时我们提供了一个最低配置的springboot demo以供测试。

你可以对 `devcontainer.json` 进行调整来适应你的个性化需求。 具体的说明文档你可以参照 [开发容器元数据参考](https://containers.dev/implementors/json_reference/)