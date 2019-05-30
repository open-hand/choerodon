[中文](https://github.com/choerodon/choerodon/blob/master/README_zh.md) | [Home](http://choerodon.io) | [Documents](http://choerodon.io/zh/docs/) | [Blog](http://choerodon.io/zh/blog/) | [Community](http://choerodon.io/zh/community/) · [Forum](http://forum.choerodon.io) | [Cases](http://choerodon.io/zh/case-studies/) | [Screenshots](https://github.com/choerodon/choerodon/blob/master/SCREENSHOT.md) | [Roadmap](https://github.com/choerodon/choerodon/blob/master/ROADMAP.md) | [Release Notes](https://github.com/choerodon/choerodon/blob/master/changelogs/)

Tips: We welcome your input! If you have feedback, please [submit an topic](http://forum.choerodon.io/) in [the forum of Choerodon](http://forum.choerodon.io/).

And you can also experience [the demo environment of Choerodon](https://organization.choerodon.com.cn/#/organization/register-organization).

# Choerodon - Open Source Multi-Cloud Application Platform

![](img/choerodon-community.png)

Choerodon is an open source multi-cloud application platform based on container orchestration and management capabilities of [Kubernetes](https://kubernetes.io/). It integrates the tool chain of DevOps, microservices, and mobile application framework to help companies achieve Scrum application delivery and automated operations management, and provide business components such as IoT, payment, data, smart insight, and enterprise application market to help companies focus on business and accelerate digital transformation.

Choerodon provides:

- A comprehensive tool chain supporting DevOps best practices, supporting Scrum management from planning, programming, building, testing, publishing, and operations.

- A suite of Spring Cloud-based microservice application frameworks to help companies become faster and more efficient for microservice development.
    
## The feature of Choerodon 
  
- [**Wiki**](http://choerodon.io/zh/docs/user-guide/wiki/) - Choerodon WiKi is a lightweight and powerful wiki platform that allows users to customize wikis based on their specific needs, provide a convenient project collaboration platform and a powerful project content management platform for enterprises and IT teams, centralize management of product-related content, manage related content, etc.

- [**Agile**](http://choerodon.io/zh/docs/user-guide/agile/) - Choerodon provides a set of tools to help users manage the flow of user value in an agile manner which consists of story map, user story, sprint, kanban.

- [**Application Management**](http://choerodon.io/zh/docs/user-guide/application-management/) - With Application Management, developers can easily create applications, make flexible application versioning, and publish applications to other projects, and can easily view projects and all applications within the organization, as well as deploy applications, through the application marketplace.

- [**Development Pipeline**](http://choerodon.io/zh/docs/user-guide/development-pipeline/) - Guided by the concept of DevOps, using Gitlab-CI as a continuous integration tool, combined with the Gitflow branch management model to provide continuous integration of the pipeline.

- [**Test Management**](http://choerodon.io/zh/docs/user-guide/test-management/) - Choerodon's Test Management provides users with an agile continuous testing tool, including test case management, test cycle, test analysis and so on, can effectively improve the software testing efficiency and quality, improve the testing flexibility and visualization level, and ultimately reduce testing time, so that users will focus on the software function construction.

- [**Deployment Pipeline**](http://choerodon.io/zh/docs/user-guide/deployment-pipeline/) - With the help of the Choerodon, users can easily manage a variety of application services that use the development and deployment of Choerodon.

- [**Operation Management**](http://choerodon.io/zh/docs/user-guide/operating-manage/) - Choerodon provides a complete set of operational management tools to monitor development indicators, server logs, application system logs, and micro service call chains.

- [**Microservice Development**](http://choerodon.io/zh/docs/development-guide/) - Choerodon provides a complete microservice development framework of Spring Cloud-based,with this development framework user can easily build application services.

Also, you can view the [screenshots of Choerodon](SCREENSHOT.md) to have a most intuitive understanding of Choerodon, and you can visit the website of Choerodon [choerodon.io](http://choerodon.io/)

## Installation
 
Please follow [the documentation of installation](http://choerodon.io/zh/docs/installation-configuration/) to install Choerodon.

## To start using Choerodon

To get started with Choerodon, please read the [Quick Start Guide](http://choerodon.io/zh/docs/quick-start/).

For operation manual, please read the documentation [choerodon.io](http://choerodon.io/zh/docs/user-guide/).

If you have any questions, you can post in [forum](http://forum.choerodon.io/).

## To start developing with Choerodon

There are two parties, **microservice backend** and **frontend**, in Choerodon microservice development framework.


If you want to develop microservice backend, please refer to the   [microservices developer's documentation](http://choerodon.io/zh/docs/development-guide/backend/).


Also, with the help of [frontend developer's documentation](http://choerodon.io/zh/docs/development-guide/front/) , you can use the Choerodon`s frontend style.

## The components of Choerodon

This repository contains the source code for Choerodon documentation. If you're looking for individual components, they live in their own repositories.

- [choerodon-starter](https://github.com/choerodon/choerodon-starters.git) - The is the toolkit developed by Choerodon and provides some basic dependency for use in the development process.

- [choerodon-framework](https://github.com/choerodon/choerodon-framework.git) - The is the Choerodon Microservices Framework.

- [api-gateway](https://github.com/choerodon/api-gateway.git) - Choerodon's gateway service is responsible for routing requests to real services. 

- [config-server](https://github.com/choerodon/config-server.git) - Choerodon's configuration service is the configuration center for unified management of service configuration files.

- [manager-service](https://github.com/choerodon/manager-service.git) - This service is the management center of the choerodon microservices framework. Its main functions include configuration management, route management, and swagger management.

- [oauth-server](https://github.com/choerodon/oauth-server.git) - This service is the authorized authentication center of the choerodon microservices framework and is mainly responsible for user privilege and authorization.

- [go-register-server](https://github.com/choerodon/go-register-server.git) - The microservice registration center is implemented by the go programming language, by tightly depend on the Kubernetes, the microservice registration is implemented by monitoring the state changes of the k8s pod, and adapt to the interface of the spring cloud eureka client to fetch service registry.

- [iam-service](https://github.com/choerodon/iam-service.git) - With management functions of user, role, permission, organization, project, password policy, fast code, client, menu, icon, multi-language , and support for importing third-party users through LDAP.

- [asgard-service](https://github.com/choerodon/easgard-service.git) - The asgard-service is a task scheduling service, and support taskOutputJsonData consistency through saga.

- [file-service](https://github.com/choerodon/file-service.git) - The file service is built on minio server, we can use minio client to upload and delete files.

- [choerodon-ui](https://github.com/choerodon/choerodon-ui.git) - An enterprise-class UI design language and React-based implementation.

- [choerodon-front](https://github.com/choerodon/choerodon-front.git) - The project is an overall front-end project that combines Choerodon iam and Choerodon devops.

- [choerodon-front-boot](https://github.com/choerodon/choerodon-front-boot.git) - Front end package management, startup, compilation.

- [agile-service](https://github.com/choerodon/agile-service.git) - The service is responsible for Agile process management and providing users with a better user experience through rich display.

- [devops-service](https://github.com/choerodon/devops-service.git) - DevOps Service is the core service of Choerodon. Integrated several open source tools to automate the process of planning, coding, building, testing, and deployment, operation, monitoring.

- [gitlab-service](https://github.com/choerodon/gitlab-service.git) - Gitlab Service is responsible for establishing communication with GitLab, handling GitLab related logic and forwarding it to other services.

- [choerodon-agent](https://github.com/choerodon/choerodon-agent.git) - It is a core component of the continuous delivery of Choerodon, deployment pipeline through active connections, and interacting directly with Kubernetes clusters, such as cluster status checks, application environment status checks, updates, and more.

- [wiki-service](https://github.com/choerodon/wiki-service.git) - This service is responsible for WiKi and wiki is a convenient project collaboration platform and a powerful project content management platform.

- [test-manager-service](https://github.com/choerodon/test-manager-service.git) - This service is responsible for Test Management and improves testing efficiency through a variety of management test plans.

- [issue-service](https://github.com/choerodon/issue-service) - It is a service that manages the flow of issue states, including checksum automation task execution before and after state conversion.

- [state-machine-service](https://github.com/choerodon/state-machine-service) - It is a service that manages the issue property settings, including problem types, states, and priorities, in the form of a scenario.

## Demo environment

And you can also experience [the demo environment of Choerodon](https://organization.choerodon.com.cn/#/organization/register-organization).

## Contribute

We welcome your input! If you have feedback, please [submit an topic](http://forum.choerodon.io/). If you'd like to participate in development, please read the [documentation of contribution](CONTRIBUTING.md) and submit a pull request.

## Support

If you have any questions and need our support, [reach out to us one way or another](http://choerodon.io/zh/community/).
