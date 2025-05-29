# 本月工作 （ 2025-2 ）

## sim_llm

### branch: ROS1

- 使用 Ultralytics 提供的 yolov8n 模型替换自训练的模型，获得了更好的识别效果：https://github.com/lalafua/sim_llm/commit/af132428e226e3c19bfd48deb23afb497fdf369e

- 完成从 ROS2 到 ROS1 的移植并发布 release：https://github.com/lalafua/sim_llm/releases/tag/ROS1-turtlesim

- 将 turtlesim 替换为 ISCAS 的建模仿真：https://github.com/lalafua/sim_llm/commit/a24138d5cd5281a589eec0e1eac57a273927087a

- 修改 prompt 引导 ai 针对具体情景思考推理：https://github.com/lalafua/sim_llm/commit/aee49425ef6cb9c569435b725e67e9383a4e3bc6

- 解决使用 roslaunch 启动节点时无法保存图片的问题：https://github.com/lalafua/sim_llm/commit/a9b5b2e7ff735e201c483c7d8e4b71c7081bafdf

- 录制演示 demo，视频地址：
    - Bilibili: https://www.bilibili.com/video/BV13BPeeSEFg/
    - Youtube: https://youtu.be/UmF9l2ZmQ8Q

- 更新说明文档并发布 release ：https://github.com/lalafua/sim_llm/releases/tag/ROS1-gazebo-v1.0.0