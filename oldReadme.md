## 如何在 cursor 中使用：

- 安装 cursor
- 在项目目录下创建 `.cursorrules`
- 复制 `thinking-claude/v4-lite-20241118.md` 内容到 `.cursorrules` 文件中
- 打开 cursor 的设置，General--Rules for AI, 启用 Include `.cursorrules` file 选项
- 测试：在 CHAT 中输入 `你能做什么`如果先有思考才输出，代表设置成功，如果没有思考出现类似`我是一个AI助手之类的` 代表设置失败。

成功：
![image](success.png)

失败：
![image](fail.png)
