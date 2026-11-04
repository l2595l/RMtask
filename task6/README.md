# task6

第六次任务：进阶部分 —— ROS2 的 **TF 坐标变换**、OpenCV **图像处理**、PyTorch **卷积神经网络**。

| 子目录 | 对应要求 | 截图 |
| --- | --- | --- |
| [ros2/01_static_tf](./ros2/01_static_tf/README.md) | 创建发布静态 TF 的文件，在 RViz 中展示 | `static_tf_rviz.jpg` |
| [ros2/02_dynamic_tf](./ros2/02_dynamic_tf/README.md) | 创建发布动态 TF 的文件：`base_link` 不动，`link1` 绕其一直旋转 | `dynamic_tf_a.png`、`dynamic_tf_b.png` |
| [opencv/01_light_bar](./opencv/01_light_bar/README.md) | 灯条识别：框出轮廓、输出 4 个端点坐标、计算中心位置 | `light_bar_detect.png` |
| [nn/01_digit_cnn](./nn/01_digit_cnn/README.md) | PyTorch 手写 CNN，摄像头端到端实时识别手写数字 | `digit_recognition_live.png`、`digit_training_curves.jpg` |

三个方向分别在两套环境里完成：TF 部分沿用《ROS2 机器人开发》配套代码 `Yuros_ros2bookcode/chapt6` 与自建的 `tf_demo_ws` 工作空间；图像处理与神经网络部分使用 Python + OpenCV + PyTorch 实现，结果通过 OpenCV 窗口实时显示，截图即窗口画面。

要求原文见 [docs/task6_requirements_ros2.png](../docs/task6_requirements_ros2.png) 与 [docs/task6_requirements_opencv_nn.png](../docs/task6_requirements_opencv_nn.png)。
