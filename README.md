# RMtask

Submit rm tasks

<img width="2275" height="1279" alt="419efa6c46f44a75dc5c3a8b4f41b99b" src="https://github.com/user-attachments/assets/fee77971-cc92-470b-bc0f-c748e9ad43d8" />

├── task1
│   └── environment     <img width="2494" height="2276" alt="image" src="https://github.com/user-attachments/assets/42c49c77-7b0b-44da-9900-adaa8f75c77f" />
 <img width="1816" height="1182" alt="image" src="https://github.com/user-attachments/assets/4fc8875b-b8c1-4e1b-896c-40e81aa3fc62" />

├── task2
│   ├── cpp
│   │   ├── 1        #入门一
│   │   └── 2        #入门二
│   └── ros        #分支结构
...

---

## 目录结构（实际归档）

```
RMtask
├── task1
│   └── environment                  # 任务一：相关环境配置
├── task3
│   └── ros
│       └── hello_world_node         # 任务三：ROS2 node 输出 Hello World
├── task5
│   ├── 01_topic_custom_msg          # 任务五-1：话题 + 自定义消息（物品信息发布/订阅）
│   ├── 02_service_custom_srv        # 任务五-2：服务 + 自定义服务接口（斐波那契）
│   └── 03_action_custom_action      # 任务五-3：动作 + 自定义动作接口（斐波那契）
└── docs                             # 任务要求与仓库结构参考图
```

## 任务索引

| 任务 | 内容 | 截图 / 记录 |
| --- | --- | --- |
| 任务一 | Ubuntu 系统安装、命令行、GitHub 登录、`colcon build` 编译工作空间 | [task1/environment](./task1/environment/README.md) |
| 任务三 | ROS2 node 编写与运行，节点打印 `Hello World` | [task3/ros/hello_world_node](./task3/ros/hello_world_node/README.md) |
| 任务五-1 | 自定义消息（物品 ID + 基本信息），发布者发布、订阅者接收并打印 | [task5/01_topic_custom_msg](./task5/01_topic_custom_msg/README.md) |
| 任务五-2 | 自定义服务接口，服务端与客户端交替输出斐波那契数列（10 项） | [task5/02_service_custom_srv](./task5/02_service_custom_srv/README.md) |
| 任务五-3 | 自定义动作接口，动作服务端反馈进度并返回最终序列 | [task5/03_action_custom_action](./task5/03_action_custom_action/README.md) |

## 参考

- [任务清单截图](./docs/task_requirements.png)
- [仓库目录结构要求](./docs/repo_structure.png)
