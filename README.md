[English](README_en.md)

# Cursor Thinking Protocol 集成指南 🤖

这个项目帮助你在 Cursor 编辑器中集成思维链，让 AI 助手能够展现出更深入的思考过程。

## ✨ 功能特点

- 启用大模型 Claude 或 QWEN 的详细思考过程
- 提供更深入的问题分析
- 生成更有质量的回答

## 🤖 支持的模型

### Claude

- 支持版本：Claude 2.0、Claude 3 Sonnet/Opus
- 配置文件：`thinking-claude/v4-lite-20241118.md`
- 特点：
  - 深度思考链路展示
  - 结构化推理过程
  - 多语言支持
  - 代码分析能力强

### Qwen（通义千问）

- 支持版本：Qwen-7B、Qwen-14B
- 配置文件：`thinking-qwen/20241119.md`
- 特点：
  - 中文思维链路优化
  - 简洁的思考展示
  - 适合国内用户
  - 响应速度快

### 使用建议

- 对于英文编程任务，推荐使用 Claude
- 对于中文交互，可以选择 Qwen
- 可以根据具体场景切换不同模型
- 建议保持模型配置文件更新到最新版本

## 🚀 安装配置

1. 首先确保已安装 [Cursor 编辑器](https://cursor.sh/)

2. 配置思考协议:

   - 在项目根目录创建 `.cursorrules` 文件
   - 将 `thinking-claude/v4-lite-20241118.md` 的内容复制到 `.cursorrules` 文件中

3. 启用配置:
   - 打开 Cursor 设置
   - 找到 `General → Rules for AI`
   - 勾选 `Include .cursorrules file` 选项

## 🔍 验证配置

在 CHAT 中输入 `你能做什么` 测试配置是否生效:

### ✅ 成功示例

- ✓ AI 会先展示思考过程
- ✓ 然后再给出具体回答

![配置成功示例](success.png)

### ❌ 失败示例

- ✗ AI 直接回答"我是一个 AI 助手"等内容
- ✗ 没有展示思考过程

![配置失败示例](fail.png)

## 🎉 效果展示

![image](thinking-claude.png)

## 💡 常见问题

1. **文件配置**

   - `.cursorrules` 文件是否在正确位置
   - 文件内容是否完整复制

2. **Cursor 设置**
   - Rules for AI 选项是否正确启用
   - Cursor 是否为最新版本

## 📝 注意事项

- 确保使用最新版本的 Cursor
- 思考协议文件会定期更新，请留意新版本

## 🔗 相关链接

- [Cursor 官网](https://cursor.sh/)
- [更多配置](https://cursor.directory/)
- [注册送 2000 万 token](https://cloud.siliconflow.cn/i/h5JiyFm0)

## ✨ 致谢

感谢 [richards199999](https://github.com/richards199999/Thinking-Claude) 提供的思考协议，让 AI 助手能够展现出更深入的思考过程。
