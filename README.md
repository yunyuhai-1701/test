# 虎牙成分浓度检测

一个趣味性的虎牙用户画像测试工具，通过20道题目测试你的虎牙DNA成分构成。

## 在线体验

🔗 [点击开始测试](https://yunyuhai-1701.github.io/test/)

## 功能特点

- **15种成分分析**：孝子、对线怪、白嫖怪、节奏带师、云玩家、阴阳人、复读机、潜水王、钓鱼佬、考古怪、破防怪、举报狗、冤种、引流狗、吃瓜怪
- **智能评价系统**：根据前两名成分组合生成专属称号和恶臭评价
- **可视化雷达图**：使用 ECharts 展示各成分占比
- **响应式设计**：支持移动端和桌面端访问
- **流畅交互**：渐变动画、悬停效果、自动跳转

## 技术栈

- 纯前端实现（HTML + CSS + JavaScript）
- [ECharts 5.4.3](https://echarts.apache.org/) - 数据可视化
- [html2canvas 1.4.1](https://html2canvas.hertzen.com/) - 截图分享（开发中）

## 本地运行

直接在浏览器中打开 `index.html` 即可。

## 项目结构

```
.
├── index.html          # 主页面（包含所有逻辑和样式）
├── README.md           # 项目说明
└── CHANGELOG.md        # 更新日志
```

## 开发说明

所有代码集中在 `index.html` 中，包括：
- 样式定义（内联 CSS）
- 题目数据（questions 数组）
- 成分定义（components 数组）
- 称号系统（badges 数组）
- 雷达图渲染逻辑（drawRadar 函数）

修改题目或成分只需编辑对应的数组即可。

## License

MIT
