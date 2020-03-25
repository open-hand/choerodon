[中文](https://github.com/choerodon/choerodon/blob/master/README_zh.md) | [Home](http://choerodon.io) | [Documents](http://choerodon.io/zh/docs/) | [Blog](http://choerodon.io/zh/blog/) | [Community](http://choerodon.io/zh/community/) · [Forum](http://forum.choerodon.io) | [Cases](http://choerodon.io/zh/case-studies/) | [Screenshots](https://github.com/choerodon/choerodon/blob/master/SCREENSHOT.md) | [Roadmap](https://github.com/choerodon/choerodon/blob/master/ROADMAP.md) | [Release Notes](https://github.com/choerodon/choerodon/blob/master/changelogs/)

Tips: We welcome your input! If you have feedback, please [submit an topic](http://forum.choerodon.io/) in [the forum of Choerodon](http://forum.choerodon.io/).

And you can also [sign up Choerodon](https://choerodon.com.cn/#/base/register-organization) and kickstart your journey.

# Choerodon - Open Source Multi-Cloud Integrated Platform

![](img/choerodon-community.png)

Choerodon is an open source mult-cloud integrated platform, which is built on open source technologies, including [Kubernetes](https://kubernetes.io/), [Istio](https://istio.io/), [knative](https://pivotal.io/knative), [Gitlab](https://about.gitlab.com/) and [Spring Cloud](https://spring.io/projects/spring-cloud), to enable integration of local and cloud environments and achieve the consistency of enterprise cloud/hybrid cloud environments. By providing Lean-Agile, continuous delivery, container environments, microservices, DevOps, and other capabilities, the platform helps organizations to manage applications lifecycle, and deliver business value rapidly and frequently.


Choerodon provides:

- A comprehensive tool chain supporting DevOps best practices, supporting Scrum management from planning, programming, building, testing, publishing, and operations.

- A suite of Spring Cloud-based microservice application frameworks to help companies become faster and more efficient for microservice development.
    
## The feature of Choerodon 
  
- [**Collaboration**](http://choerodon.io/zh/docs/user-guide/cooperation/) - Combine Lean-Agile to manage business requirements and tasks to create an efficient collaborative ecosystem. Provides collaboration tools such as worklist, story map, and knowledge management. It is a value chain that runs through development, test, and deployment. It promotes communication among team members, reduces project management costs, and improves communication and collaboration efficiency.

- [**Development**](http://choerodon.io/zh/docs/user-guide/development/) -Provides an iterative planning and continuous integration pipeline to help standardize application service development and achieve rapid iteration. Guided by the concept of DevOps, combined with lean Kanban and Gitlab branch management, it provides a continuous integration pipeline, shortens the development cycle of application services, improves team efficiency, and efficiently and frequently delivers new software versions to test teams or users.

- [**Test**](http://choerodon.io/zh/docs/user-guide/test/) -Agile continuous testing tools can effectively improve the efficiency and quality of software testing.Test Management provides users with an agile continuous testing tool, including test case management, test loop, test analysis and so on, which can effectively to improve the efficiency and quality of software testing, improve the testing flexibility and visualization level, and ultimately reduce test time and enable Users focus on building software functions.

- [**Deployment**](http://choerodon.io/zh/docs/user-guide/deploy/) -Pipelined multi-environment one-click deployment. Users can easily use the deployment function to manage various application services developed and deployed using Choerodon, including application start and stop, status monitoring, and version control corresponding to application service, container management and so on, as well as includes various involved resources management in application services, such as network, domain name, database service, cache service, etc.

- [**Operation**](http://choerodon.io/zh/docs/user-guide/report/) -Various reports that auxiliary the management of the project are collected, and display project progress details and problems in multiple dimensions. Contain agile reports (cumulative flow diagram, burndown chart， etc.), DevOps reports (code submission chart, code quality chart, etc.), test report.

- [**Microservice Development**](http://choerodon.io/zh/docs/development-guide/) - Choerodon provides a complete microservice development framework of Spring Cloud-based,with this development framework user can easily build application services.

Also, you can view the [screenshots of Choerodon](SCREENSHOT.md) to have a most intuitive understanding of Choerodon, and you can visit the website of Choerodon [choerodon.io](http://choerodon.io/)

## Installation
 
Please follow [the documentation of installation](http://choerodon.io/zh/docs/installation-configuration/) to install Choerodon.

## To start using Choerodon

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

- [manager-service](https://github.com/choerodon/manager-service.git) - This service is the management center of the choerodon microservices framework. Its main functions include configuration management, route management, and swagger management.

- [oauth-server](https://github.com/choerodon/oauth-server.git) - This service is the authorized authentication center of the choerodon microservices framework and is mainly responsible for user privilege and authorization.

- [register-server](https://github.com/choerodon/go-register-server.git) - The microservice registration center is implemented by the go programming language, by tightly depend on the Kubernetes, the microservice registration is implemented by monitoring the state changes of the k8s pod, and adapt to the interface of the spring cloud eureka client to fetch service registry.

- [base-service](https://github.com/choerodon/base-service.git) -  Choerodon's core back-end services, with user, role, privilege, organization, project, password policy, client, menu, icon, multi language and other management functions, support the import of third-party users through LDAP. 

- [asgard-service](https://github.com/choerodon/easgard-service.git) - The asgard-service is a task scheduling service, and support taskOutputJsonData consistency through saga.

- [file-service](https://github.com/choerodon/file-service.git) - The file service is built on minio server, we can use minio client to upload and delete files.

- [choerodon-ui](https://github.com/choerodon/choerodon-ui.git) - An enterprise-class UI design language and React-based implementation.Realize the react component of Material Design  of Google based on Ant Design Components , which is used to develop and serve the enterprise level back-end products.

- [choerodon-front](https://github.com/choerodon/choerodon-front.git) - The project is an overall front-end project that combines Choerodon base, Choerodon devops Choerodon agile, etc.

- [notify-service](https://github.com/choerodon/notify-service.git) - A notification service, used to send mail, station letter or SMS, as well as custom settings of various message types..

- [agile-service](https://github.com/choerodon/agile-service.git) - The service is responsible for Agile process management and the core service of the Porkfish platform. Its main functions include agile process management, including issue management, to-do items, release versions, active sprints, module management, reporting, etc.

- [devops-service](https://github.com/choerodon/devops-service.git) - DevOps Service is the core service of Choerodon. Integrated several open source tools to automate the process of planning, coding, building, testing, and deployment, operation, monitoring.

- [gitlab-service](https://github.com/choerodon/gitlab-service.git) - Gitlab Service is responsible for establishing communication with GitLab, handling GitLab related logic and forwarding it to other services.

- [choerodon-agent](https://github.com/choerodon/choerodon-agent.git) - It is a core component of the continuous delivery of Choerodon, deployment pipeline through active connections, and interacting directly with Kubernetes clusters, such as cluster status checks, application environment status checks, updates, and more.

- [test-manager-service](https://github.com/choerodon/test-manager-service.git) - The service is a test management module for Choerodon. Its main functions include test case management, test cycle, test report analysis, automated testing, etc.

- [issue-service](https://github.com/choerodon/issue-service) - It is a service that manages the flow of issue states, including checksum automation task execution before and after state conversion.

- [state-machine-service](https://github.com/choerodon/state-machine-service) - It is a service that manages the issue property settings, including problem types, states, and priorities, in the form of a scenario.

## Demo environment

And you can also experience [the demo environment of Choerodon](https://choerodon.com.cn/#/base/register-organization).

## Contribute

We welcome your input! If you have feedback, please [submit an topic](http://forum.choerodon.io/). If you'd like to participate in development, please read the [documentation of contribution](CONTRIBUTING.md) and submit a pull request.

## Support

If you have any questions and need our support, [reach out to us one way or another](http://choerodon.io/zh/community/).
