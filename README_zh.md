# Choerodon-开源多云技术平台

Choerodon猪齿鱼是一个开源多云技术平台，是基于开源技术Kubernetes，Istio，knative，Gitlab，Spring Cloud来实现本地和云端环境的集成，实现企业多云/混合云应用环境的一致性。平台通过提供精益敏捷、持续交付、容器环境、微服务、DevOps等能力来帮助组织团队来完成软件的生命周期管理，从而更快、更频繁地交付更稳定的软件。

Choerodon提供：

- 全面的工具链支持DevOps最佳实践，从计划，编程，构建，测试，发布和运营支持Scrum管理。

- 一套基于Spring Cloud的微服务应用程序框架，可帮助公司更快，更高效地进行微服务开发。

## Choerodon的特征

- [协作](http://choerodon.io/zh/docs/user-guide/cooperation/) -结合精益敏捷对业务需求、工作任务进行管理，打造高效协作生态。提供工作列表、故事地图、知识管理等协作工具，是贯穿开发、测试、部署的价值链，促进团队成员沟通交流，降低项目管理成本，提高沟通协作效率。

- [开发](http://choerodon.io/zh/docs/user-guide/development/) -提供迭代规划和持续集成的流水线，帮助规范应用服务开发，实现快速迭代。以DevOps理念为指引，结合精益看板和Gitlab的分支管理，提供持续集成的流水线，缩短应用服务开发周期，同时提高团队效率，高效频繁向测试团队或者用户交付软件新版本。

- [测试](http://choerodon.io/zh/docs/user-guide/test/) -敏捷化的持续测试工具，可以有效地提高软件测试的效率和质量。测试管理为用户提供敏捷化的持续测试工具，包括测试用例管理、测试循环、测试分析等，可以有效地提高软件测试的效率和质量，提高测试的灵活性和可视化水平，最终减少测试时间，让用户将主要精力放到软件功能构建上。

- [部署](http://choerodon.io/zh/docs/user-guide/deploy/) -流水线式多环境一键部署。用户客户可以方便地使用部署功能管理各种使用Choerodon开发部署的应用服务，包括应用启停、状态监控，以及应用服务对应的版本控制、容器管理等，同时还包括应用服务涉及到的各种资源管理，例如网络、域名、数据库服务、缓存服务等。

- [运营](http://choerodon.io/zh/docs/user-guide/report/) -汇集辅助项目进行管理的各种报表，多维度展示项目进展详情和问题。包含了敏捷报表（累积流量图、燃尽图等）、DevOps报表（代码提交图、代码质量图等）、测试报表。

另外，您可以查看Choerodon的屏幕快照以最直观地了解Choerodon，还可以访问[Choerodon](choerodon.io)的网站。

## 安装

请遵循[安装文档](http://choerodon.io/zh/docs/installation-configuration/)以安装Choerodon。

## 开始使用Choerodon

有关操作手册，请[阅读文档](http://choerodon.io/zh/docs/user-guide/)。

如有任何疑问，您可以在[论坛](https://forum.choerodon.io/)中发帖。

## 开始开发

Choerodon 微服务开发框架的开发流程。

[基础开发手册](http://choerodon.io/zh/docs/development-guide/basic/) 介绍了使用Choerodon使用到的基础组件，包括如何从使用Kubernetes的yaml部署转型到使用helm chart 进行部署等一系列入门教程。

[前端开发手册](http://choerodon.io/zh/docs/development-guide/front/) 介绍如何开发新的页面，如何建立并开发新的模块和系统平台的相关配置项。

[后端开发手册](http://choerodon.io/zh/docs/development-guide/backend/) 介绍基于开发的基本工具与其具体安装配置。通过此章节，用户可完成基本开发环境的搭建。

## Choerodon的组成

该存储库包含Choerodon文档的源代码。如果您要查找单个组件，则它们位于自己的存储库中。

- [choerodon-starter](https://github.com/choerodon/choerodon-starters) - 是Choerodon开发的工具包，提供了一些开发过程中使用的基本依赖项。
- [choerodon-framework](https://github.com/choerodon/choerodon-framework) - 是Choerodon微服务框架。
- [api-gateway](https://github.com/choerodon/api-gateway) - Choerodon的网关服务负责发送指定请求到实际的服务器。
- [manager-service](https://github.com/choerodon/manager-service)  - 该服务是Choerodon微服务开发框架的管理中心，它的主要功能包括配置管理、交付管理和 swagger 管理。
- [oauth-server](https://github.com/choerodon/oauth-server)  - 该服务是 Choerodon 微服务架构的授权认证中心, 主要负责用户权限设置和授权。
- [register-server](https://github.com/choerodon/go-register-server)  - 使用Go语言实现的注册服务，register-server与K8s紧密集成，可以监控集群中POD的状态，并可以统计注册服务客户端的信息。


- [base-service](https://github.com/choerodon/base-service)  - Choerodon的核心后端服务，具有用户、角色、权限、组织、项目、密码策略、客户端、菜单、图标、多语言等管理功能，支持通过LDAP导入第三方用户。


- [asgard-service](https://github.com/choerodon/asgard-service)  - 分布式定时任务及分布式事务管理服务。
- [file-service](https://github.com/choerodon/file-service)  - 文件服务构建在minio服务器上，我们可以使用minio客户端上传和删除文件。
- [choerodon-ui](https://github.com/choerodon/choerodon-ui)  - 基于 Ant Design Components 实现谷歌的 Material Design 的 React 组件，用于开发和服务于企业级后台产品。
- [choerodon-front](https://github.com/choerodon/choerodon-front)  - 这个前端服务是一个联合体，包含了choerodon-front-base、choerodon-front-agile、choerodon-front-devops、choerodon-front-test-manager等前端服务。
- [notify-service](https://github.com/choerodon/notify-service) - 是一个通知服务，用于发送邮件、站内信或短信，以及各消息类型的自定义设置。
- [agile-service](https://github.com/choerodon/agile-service) - 该服务是Choerodon的敏捷管理模块，是猪齿鱼平台的核心服务，它的主要功能包括敏捷流程管理，包括问题管理、待办事项、发布版本、活跃冲刺、模块管理、报告等。
- [test-manager-service](https://github.com/choerodon/test-manager-service) - 该服务是Choerodon的测试管理模块。它的主要功能包括测试用例管理、测试循环、测试报表分析、自动化测试等。
- [knowledgebase-service](https://github.com/choerodon/knowledgebase-service) - 该服务是Choerodon的知识管理模块，它的主要功能包括创建知识、编辑知识、导航、链接、搜索等。
- [choerodon-cluster-agent](https://github.com/choerodon/choerodon-cluster-agent) - Choerodon的持续交付，通过活动连接的部署管道以及与Kubernetes集群直接交互（例如集群状态检查，应用程序环境状态检查，更新等）的核心组件。
- [devops-service](https://github.com/choerodon/devops-service) - DevOps Service是 Choerodon的核心服务。集成了多个开源工具，以此形成了计划、编码、测试、部署、运维以及监控的DevOps闭环。


## 演示环境

您还可以体验Choerodon的[演示环境](https://choerodon.com.cn/#/iam/register-organization)。

## 参与贡献

我们欢迎您的参与产品设计和社区生态建设，如果您有任何反馈意见，可直接至论坛[发帖](https://forum.choerodon.io/)。如果您想参与开发，请阅读[贡献文档](https://github.com/choerodon/choerodon/blob/master/CONTRIBUTING.md)并提交请求请求。

## 支持

如果您有任何疑问并需要我们的支持，可以以这些方式[与我们联系](http://choerodon.io/zh/community/)。
