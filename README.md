# agile-front

敏捷管理服务前端代码，包括Issue管理平台，冲刺规划工作台，看板等功能。

可以用来查看和修改团队工作进度，个人工作情况，并生成相关统计信息用于分析。

## Getting Started

**项目依赖于hapcloud框架**

1. 克隆代码: `git clone http://code.saas.choerodon.com.cn/hand-rdc-choerodon/agile-front.git --recursive`  
2. 在boot和kanbanfront中分别执行`npm i`
3. 在boot下执行`gulp`（监听文件变动，不要关闭）和`npm run dev`
4. 在浏览器中输入`localhost：9090`即可查看和使用

## Menu

| 菜单     |  说明    |
| -------- | :----    |
| release  | 发布版本 |
| backlog  | 代办事项 |
| board    | 面板     |
| issue    | eipc（史诗）、故事、任务、缺陷管理平台     |

## Characteristics

1. release：
    - 规划issue：对相关issue进行查看和修改
    - 多条件查看列表：包括查询、筛选和排序
    - 创建version
2. backlog：
    - epic规划：创建、修改和删除epic并根据epic维度分类issue
    - sprint规划：创建、修改和删除sprint并根据sprint维度分类issue
    - version规划：创建、修改和删除version并根据version维度分类issue
    - issue规划工作台：实现高定制化的工作台，包括自定义拖拽排序、多条件多维度查询等
3. issue：
   - issue管理平台：多视图模式查看issue，可新建（包括简易创建）、修改、删除、排序、分类、筛选issue
   - issue评论
   - issue工作日志：通过登入工作状态和剩余的估算生成列表型的工作日志更好地追踪每天的工作进度和剩余状态
   - issue相关任务：通过issue详情中的sub-task功能实现与子任务的关联
   - 自定义label：用户可以自定义label给issue打上不同的标签，并根据标签分类、筛选等
   - issue分支管理：关联分支
   - issue附件：可对issue和issue中的评论、工作日志添加附件使描述更加详细和丰富
   - issue模块：使issue与component模块关联，在其他页面根据模块分类、筛选
   - status定义：通过对status的创建、设置，与status的内置类别相互关联，实现高度自定义
4. board
   - board设置：column与status相互对应（一列可以对应多个status），对board进行设置
   - board中issue管理：issue在board上的可自由拖拽
   - swimlane功能：自定义泳道功能

## Why is agile

  在整个过程中，设定好目标之后，以最快捷最具有价值的部分去走，保证以最快最准的态度进入开发，并在最短的周期内使团队迅速进入开发的状态

## TODO list

- [ ] User Story Map：用户故事地图
- [ ] report：报表
- [ ] history：历史记录
- [ ] 分支关联与管理

## Contributing

PRs and issues are welcome

## License

This project is licenced under the [MIT License](http://opensource.org/licenses/mit-license.html).
