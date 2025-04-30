# 2025 年 4 月工作报告

1. Lichee Pi 4A 环境搭建
    - 完成 Lichee Pi 4A 的镜像刷写与 ROS 环境安装 ([week1.md](outcome/2025_04/week1.md))。
    - 编译 YOLOX 测试用例并通过 CPU 成功运行 ([week2.md](outcome/2025_04/week2.md))。

2. NPU 功能测试
    - 针对 Lichee Pi 4A 使用 NPU（TH1520）运行 yolov5n 时遇到的问题进行排查，并成功解决 ([Issue revyos/revyos#126](https://github.com/revyos/revyos/issues/126), [week3.md](outcome/2025_04/week3.md))。

3. 文档贡献
    - 提交 PR [sipeed/sipeed_wiki#797](https://github.com/sipeed/sipeed_wiki/pull/797) 添加导出 `onnx` 模型时的必要参数 ([week2.md](outcome/2025_04/week2.md), [week3.md](outcome/2025_04/week3.md))。
    - 该 PR 已被合并 ([week4.md](outcome/2025_04/week4.md))。

4. 项目部署与验证
    - 采用多机通信的方式，成功在 Lichee Pi 4A 与其他设备间跑通项目 ([week4.md](outcome/2025_04/week4.md))。
    - 编写了多机通信部署的相关文档：[multiple_mechine.md](https://github.com/lalafua/sim_llm/blob/main/docs/multiple_mechine.md) ([week4.md](outcome/2025_04/week4.md))。
    - 录制了多机通信运行效果的演示视频：[demo_multiple_mechine.webm](https://github.com/lalafua/sim_llm/blob/main/assets/demo_multiple_mechine.webm) ([week4.md](outcome/2025_04/week4.md))。
