# Stress Smash 💥

一个酷炫的压力释放游戏网站！通过上传图片和输入名字，然后狂击目标来缓解压力。

## 功能特性

- 🎮 **互动式点击游戏** - 上传图片并疯狂点击释放压力
- 🎨 **酷炫视觉效果** - 霓虹渐变风格的暗黑UI设计
- 🔊 **音效反馈** - 每次点击都有音效反馈
- 😜 **动态语录系统** - 根据点击次数显示不同的挑衅语录
- 🎯 **彩蛋系统** - 达到特定点击数触发隐藏彩蛋
- 💻 **完全响应式** - 支持桌面、平板和手机设备
- 🎮 **作弊码系统** - 隐藏的作弊码功能

## 快速开始

### 本地运行

只需在浏览器中打开 `index.html` 文件即可！

```bash
# 如果需要本地服务器（推荐），可以使用 Python：
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 作弊码

- `roy is my sugar daddy` - +6767 点击次数
- `eugene is the master of the gooners` - +67 点击次数 + 彩蛋弹窗

## 技术栈

- 纯 HTML5
- CSS3（Flexbox + 动画）
- Vanilla JavaScript
- Google Fonts（Rajdhani & Orbitron）
- Mixkit 音效库

## 文件结构

```
roy.on99/
├── index.html      # 主网站文件
├── README.md       # 项目说明
└── .git/          # Git 版本控制
```

## 浏览器兼容性

支持所有现代浏览器：
- Chrome/Edge (最新版)
- Firefox (最新版)
- Safari (最新版)
- Mobile 浏览器

## 自定义

编辑 `index.html` 中的以下部分：
- **语录** - 修改 `quotes` 数组
- **音效** - 修改 `SOUNDS` 对象中的链接
- **颜色** - 修改 CSS 中的十六进制颜色代码
- **作弊码** - 修改 `applyCheatCode()` 函数

---

Created by Roy 🚀