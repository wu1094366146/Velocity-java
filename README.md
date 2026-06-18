### 自动构建Velocity.jar指南

1：点击Use this template ➡ Create a new repostory 创建一个私密项目

2：在Actions菜单允许 `I understand my workflows, go ahead and enable them` 按钮

3: 击下方文件名直达文件
- [Velocity.java](./proxy/src/main/java/com/velocitypowered/proxy/Velocity.java)

4: 修改`Velocity.java`文件里 149到165 行中添加需要的环境变量，不需要的留空，保存后Actions会自动构建

5：等待2分钟左右，在右侧的Release里下载velocity.jar文件

6:  上传velocity.jar到服务器根目录，点击start运行即可
