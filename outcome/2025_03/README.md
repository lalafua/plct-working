# 本月工作 （2025-3）

本月主要工作集中在从 ROS1 到 ROS2 的功能包移植、仿真测试以及文档编写。

- 利用 QEMU 启动 OpenEuler Riscv64，并成功运行 ROS2 Humble 的 turtlesim 例程

- 重新建模原有 xbot urdf 关系，优化 TF 树结构，去除冗余功能（[Commit 08927f4](https://github.com/lalafua/sim_llm/commit/08927f4324a0d1947db81fad6724e0f5acb447b4)）。
  
- 利用 Cartographer 完成系统建图（[Commit 62761ce](https://github.com/lalafua/sim_llm/commit/62761cecf44a62b2cc18f9955b5678eb47500627)）。

- 集成 nav2 导航功能包，实现简单导航服务（[Commit 37ac9ff](https://github.com/lalafua/sim_llm/commit/37ac9ff74110607814f9fc79936a92a7b4b2db54)）。

- 成功跑通各项功能测试脚本，包括导航指令传递、错误处理以及 TF 坐标变换监听，（[Commit c5d46de](https://github.com/lalafua/sim_llm/commit/c5d46de6774ce13b59210861f92e058b27684cac)）。

- 基本完成 ROS1 到 ROS2 的功能包切换，所有关键功能已全部验证（[Commit 28ff11d](https://github.com/lalafua/sim_llm/commit/28ff11ded28a7dcd49bf2e4443dfa504265d92a8)）。其中主要改进包括：
    - 自行实现 URDF 建模；
    - 建图采用 Cartographer 替换 ROS1 中的 Gmapping；
    - 导航服务迁移至 Nav2 bring_up 和 BasicNavigator。

- 录制了 ROS2 环境下的功能演示 [demo](https://github.com/lalafua/sim_llm/blob/main/assets/demo_ROS2.webm)，展示运行效果。

- 完善了项目说明[文档](https://github.com/lalafua/sim_llm/blob/main/README.md)，确保移植工作和系统优化细节均有详尽记录，并更新至主仓库文档中。
