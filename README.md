# Robot Teleoperation Console (数字孪生上位机系统)

本项目是一个基于 Web 的前端 HMI 与 ROS2 后端集成的数字孪生测试床。

## 核心功能
*   **2D/3D 实时渲染**：基于 Canvas 和 Three.js 构建的全局地图与三维视角。
*   **实时路径规划**：前端点击目标点，通过 WebSocket 发送至 ROS2，由 RRT* 算法计算避障路径。
*   **科研遥测面板**：集成 PID 调参、传感器互补滤波误差分析、实时速度与避障距离曲线。

## 注意
线上 GitHub Pages 仅展示前端 UI 交互逻辑。真实的 ROS2 数据流闭环需在本地 WSL2 环境运行。
