# 九九小课堂 🧮

一个为小学一年级小朋友设计的九九乘法表学习复习工具，纯前端实现，无需安装，打开即用。

> 🌐 **在线体验**：[https://99cal-learning.pages.dev](https://99cal-learning.pages.dev)

## ✨ 功能特色

| 模块 | 功能 |
|------|------|
| 📖 学一学 | 完整乘法表展示，点击朗读，彩色分区 |
| ✏️ 练一练 | 随机出题，可选范围和题数，即时反馈，进度追踪 |
| 🏆 闯关赛 | 三档难度，计时挑战，星星奖励 |
| 📝 摸底测 | 快速评估 / 全面评估两种模式，智能分析薄弱项 |
| 📊 成绩单 | 正确率统计，薄弱项识别，犹豫项追踪，一键专项练习 |

## 📸 预览

打开页面即可看到完整的乘法表，切换不同模块进行学习、练习、挑战和测评。

## 🚀 使用方法

### 方法一：在线访问
直接打开 [https://99cal-learning.pages.dev](https://99cal-learning.pages.dev)

### 方法二：本地打开
双击 `index.html` 文件即可在浏览器中使用。

### 方法三：本地服务器
```bash
# 使用 Python
python3 -m http.server 8080

# 使用 Node.js
npx serve .
```
然后访问 `http://localhost:8080`

## 🎨 多端适配

- ✅ 手机（竖屏/横屏）
- ✅ 平板（iPad 等）
- ✅ 电脑（各种屏幕比例）
- ✅ 支持触屏和键盘操作
- ✅ 首次访问自动检测屏幕比例，智能适配
- ✅ 支持 16:9、16:10、3:2、4:3 多种屏幕比例手动切换

## 📱 技术栈

- 纯 HTML + CSS + JavaScript（单文件，零依赖）
- 无任何第三方依赖，无需构建工具
- 使用 localStorage 本地存储学习数据
- 使用 Web Speech API 语音朗读
- 部署于 Cloudflare Pages

## 📝 更新日志

详见 [CHANGELOG.md](./CHANGELOG.md)

## 📄 开源协议

[MIT License](./LICENSE)
