# task5

第五次任务（ddl：10 月 30 日 23:59）：ROS2 的**话题 / 服务 / 动作**三大通信机制，均要求使用自定义接口。

| 子目录 | 对应要求 | 截图 |
| --- | --- | --- |
| [01_topic_custom_msg](./01_topic_custom_msg/README.md) | 自定义消息（物品 ID + 基本信息），发布者发布、订阅者接收打印 | `item_topic_pub_sub.jpg` |
| [02_service_custom_srv](./02_service_custom_srv/README.md) | 自定义服务接口，服务端与客户端交替输出斐波那契数列 | `fibonacci_service.jpg` |
| [03_action_custom_action](./03_action_custom_action/README.md) | 自定义动作接口，动作反馈进度并返回最终序列 | `fibonacci_action.png` |

三个功能包统一在 `~/ros2_learning_ws` 工作空间中，接口定义放在 `learn_interfaces` 包里，用 `colcon build` 编译后 `source install/setup.bash` 运行。
