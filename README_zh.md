简体中文 | [English](./README.md) | [官网](http://choerodon.io) | [文档](http://choerodon.io/zh/docs/) | [博客](http://choerodon.io/zh/blog/) | [社区](http://choerodon.io/zh/community/) · [论坛](http://forum.choerodon.io) | [案例](http://choerodon.io/zh/case-studies/) | [Screenshots](./SCREENSHOT.md) | [Roadmap](./ROADMAP.md) | [changelog](./changelogs/)

# Choerodon-开源全价值链多云敏捷协作平台

Choerodon猪齿鱼开源全价值链多云敏捷协作平台，是基于开源技术Kubernetes，Istio，knative，Gitlab，Spring Cloud来实现本地和云端环境的集成，实现企业多云/混合云应用环境的一致性。平台通过提供精益敏捷、持续交付、容器环境、微服务、DevOps等能力来帮助组织团队来完成软件的生命周期管理，从而更快、更频繁地交付更稳定的软件。

Choerodon提供：

- 全面的工具链支持DevOps最佳实践，从计划，编程，构建，测试，发布和运营支持Scrum管理。

- 一套基于Spring Cloud的微服务应用程序框架，可帮助公司更快，更高效地进行微服务开发。

## Choerodon的特征

- [协作](http://choerodon.io/zh/docs/user-guide/cooperation/) -结合精益敏捷对业务需求、工作任务进行管理，打造高效协作生态。提供工作列表、故事地图、知识管理等协作工具，是贯穿开发、测试、部署的价值链，促进团队成员沟通交流，降低项目管理成本，提高沟通协作效率。

- [开发](http://choerodon.io/zh/docs/user-guide/development/) -提供迭代规划和持续集成的流水线，帮助规范应用服务开发，实现快速迭代。以DevOps理念为指引，结合精益看板和Gitlab的分支管理，提供持续集成的流水线，缩短应用服务开发周期，同时提高团队效率，高效频繁向测试团队或者用户交付软件新版本。

- [测试](http://choerodon.io/zh/docs/user-guide/test/) -敏捷化的持续测试工具，可以有效地提高软件测试的效率和质量。测试管理为用户提供敏捷化的持续测试工具，包括测试用例管理、测试循环、测试分析等，可以有效地提高软件测试的效率和质量，提高测试的灵活性和可视化水平，最终减少测试时间，让用户将主要精力放到软件功能构建上。

- [部署](http://choerodon.io/zh/docs/user-guide/deploy/) -流水线式多环境一键部署。用户客户可以方便地使用部署功能管理各种使用Choerodon开发部署的应用服务，包括应用启停、状态监控，以及应用服务对应的版本控制、容器管理等，同时还包括应用服务涉及到的各种资源管理，例如网络、域名、数据库服务、缓存服务等。

- [运营](http://choerodon.io/zh/docs/user-guide/report/) -汇集辅助项目进行管理的各种报表，多维度展示项目进展详情和问题。包含了敏捷报表（累积流量图、燃尽图等）、DevOps报表（代码提交图、代码质量图等）、测试报表。

- [微服务框架](http://choerodon.io/zh/docs/development-guide/) - 基于汉得微服务技术平台HZERO的微服务架构，使用此开发框架，用户可以轻松构建应用服务。

另外，您可以查看Choerodon的屏幕快照以最直观地了解Choerodon，还可以访问[Choerodon](https://choerodon.io)的网站。

## 组件关系列表
```
└─ choerodon-parent                                CHOERODON父依赖
    ├─ choerodon-register                                注册中心服务
    ├─ choerodon-gateway                                 网关服务
    ├─ choerodon-swagger                                 swagger服务
    ├─ choerodon-admin                                   平台治理服务
    ├─ choerodon-oauth                                   认证服务
    ├─ choerodon-iam                                     IAM服务
    ├─ choerodon-platform                                平台管理服务
    ├─ choerodon-file                                    文件服务
    ├─ choerodon-monitor                                 监控服务
    ├─ choerodon-message                                 消息服务
    ├─ agile-service                                     敏捷服务
    ├─ knowledgebase-service                             知识服务
    ├─ test-manager-service                              测试服务
    ├─ devops-service                                    devops服务
    ├─ workflow-service                                  工作流服务
    ├─ gitlab-service                                    gitlab服务
    ├─ hrds-prod-repo                                    制品库服务
    ├─ hrds-code-repo                                    代码库服务
    ├─ hzero-parent                                      HZERO父依赖
    └─ choerodon-starter-parent                          通用开发父组件
        ├─ choerodon-gitlab4j-api                             gitlab api组件
        ├─ choerodon-tool-liquibase                           liquibase初始化组件 
        │  └─ hzero-installer                                 hzero初始化工具 
        ├─ choerodon-starter-core                             辅助核心开发组件 
        └─ choerodon-starter-asgard                           asgard分布式事务组件
```
欲获取HZERO-PARENT详细的组件信息，可参考[HZERO](https://github.com/open-hand/hzero.git)

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

- **choerodon-starter** [[GitHub]](https://github.com/open-hand/choerodon-starters)|[[Gitee]](https://gitee.com/open-hand/choerodon-starters) - 是Choerodon开发的工具包，提供了一些开发过程中使用的基本依赖项。
- **choerodon-framework** [[GitHub]](https://github.com/open-hand/choerodon-framework)|[[Gitee]](https://gitee.com/open-hand/choerodon-framework) - 是Choerodon微服务框架。
- **choerodon-register** [[GitHub]](https://github.com/open-hand/choerodon-register)|[[Gitee]](https://gitee.com/open-hand/choerodon-register) - 该服务Choerodon的基于Eureka的平台注册中心服务。
- **choerodon-platform** [[GitHub]](https://github.com/open-hand/choerodon-platform)|[[Gitee]](https://gitee.com/open-hand/choerodon-platform)  - 该服务是Choerodon作为平台的基础管理服务，主要为平台提供一些基础能力，如系统配置、开发配置等。
- **choerodon-oauth** [[GitHub]](https://github.com/open-hand/choerodon-oauth)|[[Gitee]](https://gitee.com/open-hand/choerodon-oauth)  - 该服务是Choerodon微服务架构的授权认证中心, 主要负责用户权限设置和授权。
- **choerodon-swagger** [[GitHub]](https://github.com/open-hand/go-choerodon-swagger)|[[Gitee]](https://gitee.com/open-hand/go-choerodon-swagger)  - 该服务是Choerodon的api文档管理服务，主要负责接口文档，平台开发测试的API文档和调试管理。
- **choerodon-gateway** [[GitHub]](https://github.com/open-hand/choerodon-gateway)|[[Gitee]](https://gitee.com/open-hand/choerodon-gateway)  - 该服务是Choerodon基于Spring Cloud Gateway的微服务网关服务。
- **choerodon-file** [[GitHub]](https://github.com/open-hand/choerodon-file)|[[Gitee]](https://gitee.com/open-hand/choerodon-file)  - 该服务是Choerodon文件管理，为平台提供文件存储服务。
- **choerodon-message** [[GitHub]](https://github.com/open-hand/choerodon-message)|[[Gitee]](https://gitee.com/open-hand/choerodon-message)  - 该服务是Choerodon消息管理，平台统一的消息推送入口。
- **choerodon-admin** [[GitHub]](https://github.com/open-hand/choerodon-admin)|[[Gitee]](https://gitee.com/open-hand/choerodon-admin)  - 该服务是Choerodon的平台治理服务，提供自动化的路由刷新、权限刷新、swagger信息刷新功能。
- **choerodon-iam** [[GitHub]](https://github.com/open-hand/choerodon-iam)|[[Gitee]](https://gitee.com/open-hand/choerodon-iam)  - 该服务是Choerodon的核心后端服务，具有用户、角色、权限、组织、项目、密码策略、客户端、菜单、图标、多语言等管理功能，支持通过LDAP导入第三方用户。
- **choerodon-asgard** [[GitHub]](https://github.com/open-hand/choerodon-asgard)|[[Gitee]](https://gitee.com/open-hand/choerodon-asgard)  - 该服务是Choerodon的分布式定时任务及分布式事务管理服务。
- **choerodon-monitor** [[GitHub]](https://github.com/open-hand/choerodon-monitor)|[[Gitee]](https://gitee.com/open-hand/choerodon-monitor)  - 该服务是Choerodon的审计监控服务，提供监控审计功能，包括数据审计和操作审计。
- **devops-service** [[GitHub]](https://github.com/open-hand/devops-service)|[[Gitee]](https://gitee.com/open-hand/devops-service) - DevOps Service是 Choerodon的核心服务。集成了多个开源工具，以此形成了计划、编码、测试、部署、运维以及监控的DevOps闭环。
- **gitlab-service** [[GitHub]](https://github.com/open-hand/gitlab-service)|[[Gitee]](https://gitee.com/open-hand/gitlab-service) - 该服务通过引入外部java客户端与Gitlab进行交互。该客户端通过直接调用Gitlab提供的api，处理来自其他服务的Gitlab请求。
- **workflow-service** [[GitHub]](https://github.com/open-hand/workflow-service)|[[Gitee]](https://gitee.com/open-hand/workflow-service) - 该服务是基于Activiti7搭建的工作流服务，支持动态灵活地创建流程，启动流程、监控流程以及管理流程

- **agile-service** [[GitHub]](https://github.com/open-hand/agile-service)|[[Gitee]](https://gitee.com/open-hand/agile-service) - 该服务是Choerodon的敏捷管理模块，是猪齿鱼平台的核心服务，它的主要功能包括敏捷流程管理，包括问题管理、待办事项、发布版本、活跃冲刺、模块管理、报告等。
- **test-manager-service** [[GitHub]](https://github.com/open-hand/test-manager-service)|[[Gitee]](https://gitee.com/open-hand/test-manager-service)  - 该服务是Choerodon的测试管理模块。它的主要功能包括测试用例管理、测试循环、测试报表分析、自动化测试等。
- **knowledgebase-service** [[GitHub]](https://github.com/open-hand/knowledgebase-service)|[[Gitee]](https://gitee.com/open-hand/knowledgebase-service) - 该服务是Choerodon的知识管理模块，它的主要功能包括创建知识、编辑知识、导航、链接、搜索等。

- **code-repo-service** [[GitHub]](https://github.com/open-hand/code-repo-service)|[[Gitee]](https://gitee.com/open-hand/code-repo-service) - 该服务是代码库管理模块，通过与Gitlab集成, 提供权限管理等功能, 通过在Choerodon平台一站式管理代码库。
- **prod-repo-service** [[GitHub]](https://github.com/open-hand/prod-repo-service)|[[Gitee]](https://gitee.com/open-hand/prod-repo-service) - 该服务是制品库模块，通过整合nexus、harbor，提供管理maven包、npm包、docker镜像等功能。

- **choerodon-ui** [[GitHub]](https://github.com/open-hand/choerodon-ui)|[[Gitee]](https://gitee.com/open-hand/choerodon-ui)  - 基于 Ant Design Components 实现谷歌的 Material Design 的 React 组件，用于开发和服务于企业级后台产品。
- **choerodon-front** [[GitHub]](https://github.com/open-hand/choerodon-front)|[[Gitee]](https://gitee.com/open-hand/choerodon-front)  - 这个前端服务是一个联合体，包含了choerodon-front-base、choerodon-front-agile、choerodon-front-devops、choerodon-front-test-manager等前端服务。
- **choerodon-front-hzero** [[GitHub]](https://github.com/open-hand/choerodon-front)|[[Gitee]](https://gitee.com/open-hand/choerodon-front)  - 这个前端服务是choerodon与hzero融合后，部分功能移植到hzero系统的前端服务，包含了用户管理、接口、API测试等功能。
- **choerodon-cluster-agent** [[GitHub]](https://github.com/open-hand/choerodon-cluster-agent)|[[Gitee]](https://gitee.com/open-hand/choerodon-cluster-agent) - Choerodon的持续交付，通过活动连接的部署管道以及与Kubernetes集群直接交互（例如集群状态检查，应用程序环境状态检查，更新等）的核心组件。


## 演示环境

您还可以体验Choerodon的[演示环境](https://choerodon.com.cn/#/iam/register-organization)。

## 参与贡献

我们欢迎您的参与产品设计和社区生态建设，如果您有任何反馈意见，可直接至论坛[发帖](https://forum.choerodon.io/)。如果您想参与开发，请阅读[贡献文档](https://github.com/open-hand/choerodon/blob/master/CONTRIBUTING.md)并提交请求请求。

## 支持

如果您有任何疑问并需要我们的支持，可以以这些方式[与我们联系](http://choerodon.io/zh/community/)。
