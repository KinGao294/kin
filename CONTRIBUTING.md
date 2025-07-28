# 🤝 贡献指南

感谢您对 Kin 个人网页项目的关注！我们欢迎所有形式的贡献。

## 🎯 如何贡献

### 📝 报告问题
- 在 [Issues](https://github.com/KinGao294/kin/issues) 页面创建新问题
- 详细描述问题，包括：
  - 浏览器版本和操作系统
  - 复现步骤
  - 预期行为和实际行为
  - 截图（如有必要）

### 💡 提出建议
- 在 Issues 页面标记为 `enhancement`
- 清楚地描述您的想法和预期效果
- 如果可能，提供设计图或示例

### 🔧 代码贡献

1. **Fork 项目**
   ```bash
   git clone https://github.com/KinGao294/kin.git
   cd kin
   ```

2. **创建功能分支**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **进行更改**
   - 保持代码风格一致
   - 添加必要的注释
   - 测试您的更改

4. **提交更改**
   ```bash
   git add .
   git commit -m "feat: 简洁描述您的更改"
   ```

5. **推送并创建 Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```

## 📋 代码规范

### HTML/CSS
- 使用 2 个空格缩进
- 保持一致的命名规范（kebab-case）
- 添加必要的注释说明

### JavaScript
- 使用现代 ES6+ 语法
- 保持函数简洁，单一职责
- 添加适当的错误处理
- 重要功能添加注释

### 提交信息规范
- `feat:` 新功能
- `fix:` 修复问题
- `docs:` 文档更新
- `style:` 样式调整
- `refactor:` 代码重构
- `test:` 测试相关
- `chore:` 构建过程或辅助工具的变动

## 🎨 设计原则

1. **用户体验优先** - 保持流畅的交互和视觉效果
2. **性能考虑** - 优化动画和资源加载
3. **响应式设计** - 确保在不同设备上正常显示
4. **可访问性** - 考虑屏幕阅读器和键盘导航
5. **浏览器兼容** - 支持主流现代浏览器

## 🚀 本地开发

1. **直接打开**
   ```bash
   # 使用 Live Server 或直接在浏览器中打开
   open index.html
   ```

2. **使用本地服务器**（推荐）
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -SimpleHTTPServer 8000
   
   # Node.js
   npx serve .
   ```

3. **访问** `http://localhost:8000`

## 🧪 测试清单

在提交 Pull Request 前，请确保：

- [ ] 在不同浏览器中测试（Chrome, Firefox, Safari, Edge）
- [ ] 移动端响应式显示正常
- [ ] BGM 播放功能正常
- [ ] 所有动画流畅运行
- [ ] 点击交互功能正常
- [ ] 没有控制台错误
- [ ] 代码格式化整洁

## 📞 联系方式

如有疑问，可以通过以下方式联系：

- **GitHub Issues**: [创建问题](https://github.com/KinGao294/kin/issues)
- **邮件**: gaokin294@gmail.com
- **即刻**: @北国桑麻

## 🎉 贡献者

感谢所有为这个项目贡献的开发者！

---

**再次感谢您的贡献！让我们一起打造更好的个人网页体验！** 🚀✨ 