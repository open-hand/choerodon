# Choerodon

![](img/choerodon-community.png)

Choerodon is an open source enterprise service platform based on container orchestration and management capabilities of [Kubernetes](https://kubernetes.io/). It integrates the tool chain of DevOps, microservices, and mobile application framework to help companies achieve Scrum application delivery and automated operations management, and provide business components such as IoT, payment, data, smart insight, and enterprise application market to help companies focus on business and accelerate digital transformation.

Choerodon provides:

- A comprehensive tool chain supporting DevOps best practices, supporting Scrum management from planning, programming, building, testing, publishing, and operations.

- A suite of Spring Cloud-based microservice application frameworks to help companies become faster and more efficient for microservice development.
    
## The feature of Choerodon 
  
- **Agile** - Choerodon provides a set of tools to help users manage the flow of user value in an agile manner which consists of story map, user story, sprint, kanban.

- [**Development Pipeline**](#) - Guided by the concept of DevOps, using Gitlab-CI as a continuous integration tool, combined with the Gitflow branch management model to provide continuous integration of the pipeline.
 
- [**Deployment Pipeline**](#) - With the help of the Choerodon, users can easily manage a variety of application services that use the development and deployment of Choerodon.

- [**Operation Management**](#) - Choerodon provides a complete set of operational management tools to monitor development indicators, server logs, application system logs, and micro service call chains.

- [**Microservice Development**](#) - Choerodon provides a complete microservice development framework of Spring Cloud-based,with this development framework user can easily build application services.

Also, you can view the [screenshots of Choerodon](SCREENSHOT.md) to have a most intuitive understanding of Choerodon, and you can visit the website of Choerodon [choerodon.io](http://choerodon.io/)

## Installation
 
Please follow [the documentation of installation](http://choerodon.io/zh/docs/installation-configuration/) to install Choerodon.

## To start using Choerodon

To get started with Choerodon, please read the [Quick Start Guide](http://choerodon.io/zh/docs/quick-start/).

For operation manual, please read the documentation [choerodon.io](http://choerodon.io/zh/docs/user-guide/).

## To start developing with Choerodon

There are two parties, **microservice backend** and **frontend**, in Choerodon microservice development framework.


If you want to develop microservice backend, please refer to the   [microservices developer's documentation](http://choerodon.io/zh/docs/development-guide/backend/).


Also, with the help of [frontend developer's documentation](http://choerodon.io/zh/docs/development-guide/front/) , you can use the Choerodon`s frontend style.

## The components of Choerodon

This repository contains the source code for Choerodon documentation. If you're looking for individual components, they live in their own repositories.

- [choerodon-starter-parent](https://github.com/choerodon/choerodon-starter-parent.git) - Basic Component
- [api-gateway](https://github.com/choerodon/api-gateway.git) - Request routing forwarding 
- [register-server](https://github.com/choerodon/go-register-server.git) - Microservice registry center
- [config-server](https://github.com/choerodon/config-server.git) - A configuration center for unified management of service configuration files
- [mamager-service](https://github.com/choerodon/manager-service.git) - Manage the configuration of all services, gateway routing, Swagger documents
- [gateway-helper](https://github.com/choerodon/gateway-helper.git) - Permissions check, current limiting
- [oauth-server](https://github.com/choerodon/oauth-server.git) - Authentication
- [eureka-server](https://github.com/choerodon/eureka-server.git) - Locally initiated registration services 
- [iam-service](https://github.com/choerodon/iam-service.git) - IAM management and certification management
- [event-store-service](https://github.com/choerodon/event-store-service.git) - Event conformance management
- [file-service](https://github.com/choerodon/file-service.git) - File uploading and downloading
- [hystrix-turbine](https://github.com/choerodon/hystrix-turbine.git) - Hystrix stream polymerization
- [hystrix-dashboard](https://github.com/choerodon/hystrix-dashboard.git) - hystrix Dashboard
- [notification-service](https://github.com/choerodon/notification-service.git) - Management and notification of token
- [boot](https://github.com/choerodon/front_boot.git) - Front end package management, startup, compilation
- [choerodon-front](https://github.com/choerodon/choerodon-front.git) - Front-end framework project
- [choerodon-front-parent](https://github.com/choerodon/choerodon-front.git) - Total front-end projects
- [devops-service](https://github.com/choerodon/devops-service.git) - DevOps service
- [gitlab-service](https://github.com/choerodon/gitlab-service.git) - Gitlab service
- [devops-front](https://github.com/choerodon/devops-front.git) - DevOps front-end
- [env-agent](https://github.com/choerodon/env-agent.git) - Environment client
- [agile-service](https://github.com/choerodon/agile-service.git) - Agile management service
- [agile-front](https://github.com/choerodon/agile-front.git) - Agile management front-end 

## Contribute

We welcome your input! If you have feedback, please [submit an issue](https://github.com/choerodon/choerodon/issues). If you'd like to participate in development, please read the [documentation of contribution](contributing.md) and submit a pull request.

## Support

If you have any questions and need our support, [reach out to us one way or another]
(http://choerodon.io/zh/community/).

