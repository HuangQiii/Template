# agile-front

敏捷管理服务前端代码，包括待办事项、活动的冲刺、面板、发布版本等功能。

可以用来查看和修改团队工作进度，个人工作情况，并生成相关统计信息用于分析。

## Why is agile

我们认为软件交付过程的本质是用户价值的实现，而用户价值的实现是通过用户价值流动来体现的，为此我们提供了一套工具来帮助用户通过敏捷的方式来管理用户价值的流动，使整个软件开发流程管理化规范化。

在整个过程中，设定好目标之后，向最快捷且最具价值的部分去开展，在最短的周期内使团队进入开发状态

## Getting Started

**项目依赖于choerodon前端框架**

1. 克隆代码: `git clone http://code.saas.choerodon.com.cn/hand-rdc-choerodon/agile-front.git --recursive`  

2. 在boot和agilefront中分别执行`npm i`

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

1. 可多条件多维度查询的issue工作台，更方便地查看issue

2. 可自由拖拽的backlog工作台，迅速查看工作情况

3. 高粒度的issue功能，包括标签、模块等自定义字段，方便用户更好地检索和查看自己感兴趣的内容，还包括评论、工作日志等功能，追踪每天的工作进度和剩余情况，制定新计划，与分支的关联使开发更加方便

4. 简易但强大的看板，可以自定义看板列的状态（一列对应一或多个状态），自定义关注的看板列，形式多样且操作方便，直观展现工作进度

## TODO list

- [ ] User Story Map：用户故事地图
- [ ] Report：报表和数据分析
- [ ] History：历史记录
- [ ] 分支关联与管理

## Contributing

PRs and issues are welcome

## License

This project is licenced under the [MIT License](http://opensource.org/licenses/mit-license.html).
