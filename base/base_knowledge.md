# git 基础知识

## 基本命令

- 1、查看所有的配置以及它们所在的文件：

    > git config --list --show-origin
- 2、设置用户名及邮件
    > git config --global user.name "John Doe"
    >
    > git config --global user.email johndoe@example.com

    ```js
    如果使用了 --global 选项，那么该命令只需要运行一次，因为之后无论你在该系统上做任何事情， Git 都会使用那些信息。 当你想针对特定项目使用不同的用户名称与邮件地址时，可以在那个项目目录下运行没有 --global 选项的命令来配置
    ```

- 3、检查配置信息
    > git config --list
