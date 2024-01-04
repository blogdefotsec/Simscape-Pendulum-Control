# README（CH）

## 基于Simscape的动量轮控制单摆仿真系统

这是一个基于Simscape的动量轮控制单摆仿真系统。通过模拟电机（输入PWM）连接至动量轮，改变单摆的运动状态。

包含了以下功能：

- 单摆的震荡回复
- 单摆的非震荡回复
- 单摆的倒立控制
- 可调PID模式
- 阶跃干扰引入

模型含有一个完整的电机和单摆模型供二次开发。摆杆和电机均已封装为子函数供移植使用。

## 演示视频

稍后上传……

## 依赖

版本信息：该模型使用Matlab R2022A建立，建议您的版本不小于该版本以获得最佳的运行状态。

要运行该模型，你至少需要以下Toolbox：

- Simscape、Simscape Multibody、Simscape Electrical

要对PID参数进行二次开发，我还建议您使用以下Toolbox：

- System Identification
- Simulink Control Design

## 快速开始

单机Simulink上方的“运行”按钮，等待渲染后开启。

模式选择部分在下方，单击旋钮使其处于高亮状态，随后可以进行调整。