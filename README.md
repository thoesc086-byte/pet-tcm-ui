# 宠物中医药 App · 设计 Demo

> 一个面向宠物的中医药调理 App 概念设计，以 HTML 单页 Demo 形式呈现。

## 🐾 模块

| Tab | 内容 |
|---|---|
| **检测** (首页) | 健康检测三状态流程：开始 → 扫描动画 → 结果报告 |
| **药浴** (恢复) | 智能药浴盆控制面板：水温/熬药/水循环/UV杀菌 |
| **放松** | 智能按摩衣 + 经络舒缓视图 + 按摩模式 + 趋势 |
| **空间** | 草本狗窝：实时环境/草本配方/睡眠监测/环境调节 |

## 🚀 快速预览

直接打开 `index.html` 即可，或起一个本地 server：

```bash
python3 -m http.server 9876
# 访问 http://localhost:9876
```

## 🎨 设计 Token

```css
--bg: #FBF4EE       /* 米白底 */
--card: #FEFAF7
--primary: #7797C0  /* 柔和蓝 */
--text: #3A3833
--good: #8AAE8E     /* 绿 */
--warn: #D9B271     /* 金 */
--danger: #C97B7B   /* 红 */
```

## 📐 技术

- 纯 HTML + CSS + 原生 JS（零依赖）
- 所有 icon 为内联 SVG
- 手机模拟尺寸：375×812（iPhone 标准）

## 📂 目录

```
pet-tcm-ui/
├── index.html         # 主入口
├── 01-检测模块/        # 检测模块原始 mockup 切图
├── refs/              # 4 个 Tab 的参考 mockup
└── preview/           # Tab 截图
```

## 🌿 药材图片来源

所有药材照片均来自 [Wikimedia Commons](https://commons.wikimedia.org/) 公共领域 / CC 授权：

| 中文名 | 学名 | 用途 |
|---|---|---|
| 金银花 | Lonicera japonica | 药浴 |
| 苦参 | Sophora flavescens | 药浴 |
| 艾叶 | Artemisia argyi | 药浴 |
| 黄柏 | Phellodendron amurense | 药浴 |
| 薄荷 | Mentha | 药浴 / 活力 |
| 薰衣草 | Lavandula | 安神 |
| 茉莉 | Jasminum sambac | 安神 |
| 柏木 | Cupressus | 睡眠 |
| 檀香 | Santalum album | 睡眠 |
| 青草 | Grass | 雨天舒缓 |
| 苔藓 | Bryophyta | 雨天舒缓 |
| 柠檬 | Lemon | 活力 |
