[Home](http://choerodon.io) | [Documents](http://choerodon.io/zh/docs/) | [Blog](http://choerodon.io/zh/blog/) | [Community](http://choerodon.io/zh/community/) · [Forum](http://forum.choerodon.io) | [Cases](http://choerodon.io/zh/case-studies/) | [Screenshots](https://github.com/choerodon/choerodon/blob/master/SCREENSHOT.md) | [Roadmap](https://github.com/choerodon/choerodon/blob/master/ROADMAP.md) | [Release Notes](https://github.com/choerodon/choerodon/blob/master/changelogs/)

# Choerodon - An open source PaaS for Kubernetes

![](img/choerodon-community.png)

Choerodon is an open source enterprise service platform based on container orchestration and management capabilities of [Kubernetes](https://kubernetes.io/). It integrates the tool chain of DevOps, microservices, and mobile application framework to help companies achieve Scrum application delivery and automated operations management, and provide business components such as IoT, payment, data, smart insight, and enterprise application market to help companies focus on business and accelerate digital transformation.

Choerodon provides:

- A comprehensive tool chain supporting DevOps best practices, supporting Scrum management from planning, programming, building, testing, publishing, and operations.

- A suite of Spring Cloud-based microservice application frameworks to help companies become faster and more efficient for microservice development.
    
## The feature of Choerodon 
  
- [**Wiki**](http://v0-8.choerodon.io/zh/docs/user-guide/wiki/) - Choerodon WiKi is a lightweight and powerful wiki platform that allows users to customize wikis based on their specific needs, provide a convenient project collaboration platform and a powerful project content management platform for enterprises and IT teams, centralize management of product-related content, manage related content, etc.

- [**Agile**](http://v0-8.choerodon.io/zh/docs/user-guide/agile/) - Choerodon provides a set of tools to help users manage the flow of user value in an agile manner which consists of story map, user story, sprint, kanban.

- [**Application Management**](http://v0-8.choerodon.io/zh/docs/user-guide/application-management/) - With Application Management, developers can easily create applications, make flexible application versioning, and publish applications to other projects, and can easily view projects and all applications within the organization, as well as deploy applications, through the application marketplace.

- [**Development Pipeline**](http://v0-8.choerodon.io/zh/docs/user-guide/development-pipeline/) - Guided by the concept of DevOps, using Gitlab-CI as a continuous integration tool, combined with the Gitflow branch management model to provide continuous integration of the pipeline.

- [**Test Management**](http://v0-8.choerodon.io/zh/docs/user-guide/test-management/) - Choerodon's Test Management provides users with an agile continuous testing tool, including test case management, test cycle, test analysis and so on, can effectively improve the software testing efficiency and quality, improve the testing flexibility and visualization level, and ultimately reduce testing time, so that users will focus on the software function construction.

- [**Deployment Pipeline**](http://v0-8.choerodon.io/zh/docs/user-guide/deployment-pipeline/) - With the help of the Choerodon, users can easily manage a variety of application services that use the development and deployment of Choerodon.

- [**Operation Management**](http://v0-8.choerodon.io/zh/docs/user-guide/operating-manage/) - Choerodon provides a complete set of operational management tools to monitor development indicators, server logs, application system logs, and micro service call chains.

- [**Microservice Development**](http://v0-8.choerodon.io/zh/docs/development-guide/) - Choerodon provides a complete microservice development framework of Spring Cloud-based,with this development framework user can easily build application services.

Also, you can view the [screenshots of Choerodon](SCREENSHOT.md) to have a most intuitive understanding of Choerodon, and you can visit the website of Choerodon [choerodon.io](http://v0-8.choerodon.io/)

## Installation
 
Please follow [the documentation of installation](http://v0-8.choerodon.io/zh/docs/installation-configuration/) to install Choerodon.

## To start using Choerodon

To get started with Choerodon, please read the [Quick Start Guide](http://v0-8.choerodon.io/zh/docs/quick-start/).

For operation manual, please read the documentation [choerodon.io](http://v0-8.choerodon.io/zh/docs/user-guide/).

## To start developing with Choerodon

There are two parties, **microservice backend** and **frontend**, in Choerodon microservice development framework.


If you want to develop microservice backend, please refer to the   [microservices developer's documentation](http://v0-8.choerodon.io/zh/docs/development-guide/backend/).


Also, with the help of [frontend developer's documentation](http://v0-8.choerodon.io/zh/docs/development-guide/front/) , you can use the Choerodon`s frontend style.

## The components of Choerodon

This repository contains the source code for Choerodon documentation. If you're looking for individual components, they live in their own repositories.

- [choerodon-starter](https://github.com/choerodon/choerodon-starters.git) - The is the toolkit developed by Choerodon and provides some basic dependency for use in the development process.
- [choerodon-framework](https://github.com/choerodon/choerodon-framework.git) - The is the Choerodon Microservices Framework.
- [go-register-server](https://github.com/choerodon/go-register-server.git) - The microservice registration center is implemented in the go language, by tightly integrating the Kubinertes, the microservice registration is implemented by monitoring the state changes of the k8s
