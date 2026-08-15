# Lab 03: DQN on CartPole

这是“深度学习基础”课程的第三次作业，使用 PyTorch 和 Gymnasium 实现 Deep Q-Network（DQN），并在 `CartPole-v1` 环境中进行训练和评估。

## 主要内容

- 使用 PyTorch 构建 DQN
- 实现经验回放（Replay Buffer）
- 使用 epsilon-greedy 策略选择动作
- 使用目标网络计算 TD 目标
- 绘制训练奖励和损失曲线
- 在 CartPole 环境中评估智能体

## 文件

- `DQN_Lab_第三次作业.ipynb`：实验代码、训练过程和结果

## 运行环境

```bash
pip install "gymnasium[classic-control]" torch matplotlib numpy
```
## 说明

本项目为个人课程学习记录，用于整理实验过程和代码实现。
