# 坦克大战

一个基于 HTML5 Canvas 的经典坦克大战游戏，无需任何依赖，直接在浏览器中运行。

![游戏截图](https://img.shields.io/badge/游戏-坦克大战-f0c040?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-e34c26?style=flat-square&logo=html5)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## 在线游玩

> GitHub Pages 部署后可直接访问：  
> **https://xirahane.github.io/tank-battle**

或者克隆仓库后，直接用浏览器打开 `index.html` 即可。

## 游戏玩法

| 按键 | 操作 |
|------|------|
| `W` / `↑` | 向上移动 |
| `S` / `↓` | 向下移动 |
| `A` / `←` | 向左移动 |
| `D` / `→` | 向右移动 |
| `空格` / `J` | 发射子弹 |

**目标：** 消灭所有敌方坦克，保护屏幕中央下方的基地（★）不被摧毁。

## 游戏特性

- **10 个关卡** — 随关卡增加，敌人数量更多、速度更快
- **4 种敌方坦克** — 不同颜色，高关卡敌人拥有双倍血量
- **地图障碍物**
  - 🟫 砖块墙 — 可被子弹摧毁
  - ⬜ 钢铁墙 — 无法被子弹穿透
- **基地保卫** — 基地被摧毁立即游戏结束
- **3 条生命** — 被击中后可原地复活
- **爆炸特效** — 粒子爆炸动画效果
- **计分系统** — 击杀敌人得分，关卡越高分值越高

## 快速开始

```bash
git clone https://github.com/xirahane/tank-battle.git
cd tank-battle
# 用浏览器打开 index.html
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

## 项目结构

```
tank-battle/
└── index.html    # 游戏全部代码（HTML + CSS + JavaScript）
```

## 技术栈

- **HTML5 Canvas** — 游戏渲染
- **原生 JavaScript** — 游戏逻辑、AI、碰撞检测
- **CSS3** — UI 样式与布局
- 无任何第三方依赖

## License

[MIT](https://opensource.org/licenses/MIT)
