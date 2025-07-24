# 外星人入侵 (Alien Invasion)

一个使用Python和Pygame开发的经典太空射击游戏，玩家控制飞船抵御外星人入侵。

## 游戏简介
在这款游戏中，玩家将控制一艘宇宙飞船，在屏幕底部移动并射击外星人。外星人会不断向下移动，玩家需要在它们到达屏幕底部前将其全部消灭。随着游戏进行，外星人的移动速度会逐渐增加，挑战玩家的反应能力。

## 功能特点
- 流畅的游戏动画和控制体验
- 逐步增加的游戏难度
- 完整的计分系统
- 生命值显示和游戏状态管理
- 开始菜单和游戏重置功能

## 安装说明

### 前提条件
- Python 3.6或更高版本
- Pygame库

### 安装步骤
1. 克隆本仓库
```bash
git clone https://github.com/yourusername/alien-invasion.git
cd alien-invasion
```

2. 安装依赖
```bash
pip install pygame
```

## 如何游戏

### 运行游戏
```bash
python alien_invasion.py
```

### 游戏控制
- **左右方向键**：移动飞船
- **空格键**：发射子弹
- **Q键**：退出游戏
- **P键**：暂停/继续游戏
- **开始按钮**：开始新游戏

## 项目结构
```
├── alien.py           # 外星人类
├── alien_invasion.py  # 游戏主程序
├── bullet.py          # 子弹类
├── button.py          # 按钮类
├── game_stats.py      # 游戏状态管理
├── scoreboard.py      # 计分板
├── settings.py        # 游戏设置
├── ship.py            # 飞船类
└── image/             # 游戏图像资源
    ├── alien.bmp
    └── ship.bmp
```

## 开发计划
- [ ] 添加不同类型的外星人
- [ ] 实现武器升级系统
- [ ] 添加音效和背景音乐
- [ ] 增加游戏关卡
- [ ] 实现高分榜功能

## 许可证
[MIT](https://opensource.org/licenses/MIT)

## 致谢
本项目基于《Python编程：从入门到实践》一书中的示例项目扩展而来。
        
