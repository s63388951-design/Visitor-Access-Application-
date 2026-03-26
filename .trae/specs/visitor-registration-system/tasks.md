# Tasks

## Phase 1: 小程序端开发

- [ ] Task 1: 创建小程序端项目基础结构
  - [ ] SubTask 1.1: 初始化小程序项目框架
  - [ ] SubTask 1.2: 配置页面路由和导航
  - [ ] SubTask 1.3: 创建公共组件库

- [ ] Task 2: 实现扫码落地页
  - [ ] SubTask 2.1: 创建二维码扫描入口页面
  - [ ] SubTask 2.2: 实现访客类型选择功能（探亲访友、家政维修、房屋中介、外卖、快递）
  - [ ] SubTask 2.3: 实现页面跳转逻辑

- [ ] Task 3: 实现探亲访友/房屋中介/家政维修登记页
  - [ ] SubTask 3.1: 创建房号选择组件（对接ERP数据）
  - [ ] SubTask 3.2: 创建被访人信息填写表单
  - [ ] SubTask 3.3: 实现小程序一键登录获取手机号
  - [ ] SubTask 3.4: 实现访客姓名填写
  - [ ] SubTask 3.5: 实现信息核对逻辑（3种信息核对成功2种）

- [ ] Task 4: 实现外卖/快递登记页
  - [ ] SubTask 4.1: 创建简化登记表单
  - [ ] SubTask 4.2: 实现一键登录获取手机号
  - [ ] SubTask 4.3: 实现访客姓名填写

- [ ] Task 5: 实现通行二维码功能
  - [ ] SubTask 5.1: 创建通行码生成服务
  - [ ] SubTask 5.2: 创建待放行码生成服务
  - [ ] SubTask 5.3: 实现二维码展示页面（含动态时间）
  - [ ] SubTask 5.4: 实现24小时有效期验证

- [ ] Task 6: 实现业主审批功能
  - [ ] SubTask 6.1: 创建业主审核通知接收页面
  - [ ] SubTask 6.2: 创建审核操作页面（通过/不通过）
  - [ ] SubTask 6.3: 实现审核结果通知推送

## Phase 2: 企微端开发

- [ ] Task 7: 创建企微端项目基础结构
  - [ ] SubTask 7.1: 初始化企微应用项目
  - [ ] SubTask 7.2: 配置企微应用入口
  - [ ] SubTask 7.3: 创建公共组件库

- [ ] Task 8: 实现来访记录列表
  - [ ] SubTask 8.1: 创建记录列表页面
  - [ ] SubTask 8.2: 实现时间倒序排列
  - [ ] SubTask 8.3: 实现状态筛选（待审核、已通过、不通过）
  - [ ] SubTask 8.4: 实现分页加载

- [ ] Task 9: 实现访客详情页
  - [ ] SubTask 9.1: 创建访客详情展示页面
  - [ ] SubTask 9.2: 显示访客类型、房号、被访人信息等

- [ ] Task 10: 实现审核功能
  - [ ] SubTask 10.1: 创建扫码审核入口
  - [ ] SubTask 10.2: 创建审核操作页面（通过/不通过）
  - [ ] SubTask 10.3: 实现转发业主审核功能
  - [ ] SubTask 10.4: 实现审核结果更新

## Phase 3: PC管理端开发

- [ ] Task 11: 创建PC管理端项目基础结构
  - [ ] SubTask 11.1: 初始化PC端项目框架
  - [ ] SubTask 11.2: 实现用户登录和权限验证
  - [ ] SubTask 11.3: 创建布局框架（侧边栏、头部导航）

- [ ] Task 12: 实现权限管理
  - [ ] SubTask 12.1: 实现项目管理员权限控制
  - [ ] SubTask 12.2: 实现地区管理员权限控制
  - [ ] SubTask 12.3: 实现集团管理员权限控制
  - [ ] SubTask 12.4: 实现数据权限过滤

- [ ] Task 13: 实现项目二维码管理
  - [ ] SubTask 13.1: 创建二维码管理页面
  - [ ] SubTask 13.2: 实现二维码查看和下载
  - [ ] SubTask 13.3: 实现二维码启用/禁用功能

- [ ] Task 14: 实现访客统计
  - [ ] SubTask 14.1: 创建访客历史记录列表页面
  - [ ] SubTask 14.2: 实现记录查询和筛选
  - [ ] SubTask 14.3: 创建统计图表组件
  - [ ] SubTask 14.4: 实现数据导出功能

## Phase 4: 后端服务开发

- [ ] Task 15: 创建后端服务基础架构
  - [ ] SubTask 15.1: 设计数据库表结构
  - [ ] SubTask 15.2: 创建API接口框架
  - [ ] SubTask 15.3: 实现用户认证服务

- [ ] Task 16: 实现核心业务接口
  - [ ] SubTask 16.1: 实现访客登记接口
  - [ ] SubTask 16.2: 实现信息核对接口
  - [ ] SubTask 16.3: 实现二维码生成接口
  - [ ] SubTask 16.4: 实现审核接口
  - [ ] SubTask 16.5: 实现ERP数据对接接口

- [ ] Task 17: 实现消息推送服务
  - [ ] SubTask 17.1: 实现企微消息推送
  - [ ] SubTask 17.2: 实现小程序订阅消息推送

# Task Dependencies

- Task 2 依赖 Task 1
- Task 3 依赖 Task 1
- Task 4 依赖 Task 1
- Task 5 依赖 Task 3, Task 4
- Task 6 依赖 Task 5
- Task 8 依赖 Task 7
- Task 9 依赖 Task 8
- Task 10 依赖 Task 9
- Task 12 依赖 Task 11
- Task 13 依赖 Task 12
- Task 14 依赖 Task 12
- Task 16 依赖 Task 15
- Task 17 依赖 Task 15
