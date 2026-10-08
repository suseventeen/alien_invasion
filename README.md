# Alien Invasion

学生时期使用 Python / Pygame 编写的外星人射击练习项目，作为学习记录保留，不承诺持续维护。

## 功能

- 点击 Play 开始游戏。
- 左右方向键移动，空格发射子弹，Q 退出。
- 外星人阵列、碰撞检测、得分、最高分和关卡升级。

## 运行

从仓库根目录执行：

```sh
python -m venv .venv
python -m pip install -r requirements.txt
python alien_invasion.py
```

创建虚拟环境后，请先按操作系统的方式激活它，再运行安装和启动命令。

原仓库环境为 Python 3.7 / Pygame 1.9.6。依赖清单保留原 Pygame 版本，用于记录历史环境；尚未验证在当前 Python 版本上的安装与运行兼容性。图片按相对路径读取，需从根目录启动。

## 整理说明

移除提交中的虚拟环境、字节码缓存和个人 IDE 配置；保留源码、图片和原有提交历史。仅整理仓库与文档，未修复原有游戏逻辑。
