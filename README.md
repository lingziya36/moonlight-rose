# 🌹 月光蔷薇学园：命运的约定

一款百合向视觉小说游戏

## 📱 获取APK（无需电脑）

### 方法一：GitHub Actions自动构建（推荐）

1. **Fork这个仓库**
   - 点击页面右上角的 "Fork" 按钮

2. **触发构建**
   - 进入你Fork的仓库
   - 点击 "Actions" 标签
   - 点击 "Build Android APK" → "Run workflow"
   - 等待约5分钟

3. **下载APK**
   - 点击 "Releases"
   - 下载 `app-debug.apk`
   - 安装到手机即可游玩

### 方法二：在线打包工具

- [WebIntoApp](https://webintoapp.com/) - 免费在线打包
- [GoNative](https://gonative.io/) - 另一种选择

输入网址：你的游戏网页地址

## 🎮 游戏特色

- 精美哥特风视觉小说
- 暖暖风格换装系统
- 凌子养成互动
- CG收集画廊
- 离线可玩

## 📂 项目结构

```
├── www/              # 游戏文件
│   └── index.html    # 主页面
├── config.xml        # Cordova配置
├── package.json      # 项目配置
└── .github/workflows/# 自动构建脚本
```

## 🔧 技术栈

- Cordova - 混合应用框架
- HTML5/CSS3/JavaScript - 游戏核心
- GitHub Actions - 自动构建

## 📄 许可

© 月光蔷薇学园制作组
