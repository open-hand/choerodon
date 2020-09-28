English | [简体中文](./README_zh.md) | [Home](http://choerodon.io) | [Documents](http://choerodon.io/zh/docs/) | [Blog](http://choerodon.io/zh/blog/) | [Community](http://choerodon.io/zh/community/) · [Forum](http://forum.choerodon.io) | [Cases](http://choerodon.io/zh/case-studies/) | [Screenshots](https://github.com/choerodon/choerodon/blob/master/SCREENSHOT.md) | [Roadmap](https://github.com/choerodon/choerodon/blob/master/ROADMAP.md) | [Release Notes](https://github.com/choerodon/choerodon/blob/master/changelogs/)


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

## Component relationship list
```
└─ choerodon-parent                                CHOERODON Father component
    ├─ hzero-parent                                HZERO Father component
    └─ choerodon-starter-parent                    Generic development parent component
        ├─ choerodon-gitlab4j-api                  gitlab api component
        ├─ choerodon-tool-liquibase                liquibase Initialize component
        │  └─ hzero-installer                      hzero Initialize component 
        ├─ choerodon-starter-core                  core component
        └─ choerodon-starter-asgard                asgard component
```
For detailed component information on HZERO-PARENT，see[HZERO](https://github.com/open-hand/hzero.git).


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
- **choerodon-starter** [[GitHub]](https://github.com/open-hand/choerodon-starters)|[[Gitee]](https://gitee.com/open-hand/choerodon-starters) - Is a toolkit developed by Choerodon, which provides some of the basic dependencies used in the development process.
- **choerodon-framework** [[GitHub]](https://github.com/open-hand/choerodon-framework)|[[Gitee]](https://gitee.com/open-hand/choerodon-framework) - Choerodon microservices framework.
- **choerodon-register** [[GitHub]](https://github.com/open-hand/choerodon-register)|[[Gitee]](https://gitee.com/open-hand/choerodon-register) - The service Choerodon's Platform registry service is based on Eureka.
- **choerodon-platform** [[GitHub]](https://github.com/open-hand/choerodon-platform)|[[Gitee]](https://gitee.com/open-hand/choerodon-platform)  - This service is Choerodon as the basic management service of the platform, mainly providing some basic capabilities for the platform, such as system configuration, development configuration, etc.
- **choerodon-oauth** [[GitHub]](https://github.com/open-hand/choerodon-oauth)|[[Gitee]](https://gitee.com/open-hand/choerodon-oauth)  - This service is the Choerodon microservice architecture authorization center and is mainly responsible for user permission setting and authorization.
- **choerodon-swagger** [[GitHub]](https://github.com/open-hand/go-choerodon-swagger)|[[Gitee]](https://gitee.com/open-hand/go-choerodon-swagger)  - This service is Choerodon's API document management service, which is mainly responsible for interface document, API document of platform development test and debugging management.
- **choerodon-gateway** [[GitHub]](https://github.com/open-hand/choerodon-gateway)|[[Gitee]](https://gitee.com/open-hand/choerodon-gateway)  - This service is Choerodon's Spring Cloud Gateway based microservice Gateway service.
- **choerodon-file** [[GitHub]](https://github.com/open-hand/choerodon-file)|[[Gitee]](https://gitee.com/open-hand/choerodon-file)  - The service is Choerodon file management, which provides file storage services for the platform.
- **choerodon-message** [[GitHub]](https://github.com/open-hand/choerodon-message)|[[Gitee]](https://gitee.com/open-hand/choerodon-message)  - The service is Choerodon message management, a unified messaging push portal for the platform.
- **choerodon-admin** [[GitHub]](https://github.com/open-hand/choerodon-admin)|[[Gitee]](https://gitee.com/open-hand/choerodon-admin)  - This service is Choerodon's platform governance service and provides automated routing refresh, authority refresh, swagger information refresh.
- **choerodon-iam** [[GitHub]](https://github.com/open-hand/choerodon-iam)|[[Gitee]](https://gitee.com/open-hand/choerodon-iam)  - This service is the core back-end service of Choerodon, with administrative functions such as user, role, permission, organization, project, password policy, client, menu, icon, multi-language, etc., supporting the import of third-party users through LDAP.
- **choerodon-asgard** [[GitHub]](https://github.com/open-hand/choerodon-asgard)|[[Gitee]](https://gitee.com/open-hand/choerodon-asgard)  - This service is Choerodon's distributed timing task and distributed transaction management service.
- **choerodon-monitor** [[GitHub]](https://github.com/open-hand/choeordon-monitor)|[[Gitee]](https://gitee.com/open-hand/choerodon-monitor)  - This service is Choerodon's audit monitoring service and provides monitoring audit capabilities, including data audit and operational audit.

- **devops-service** [[GitHub]](https://github.com/open-hand/devops-service)|[[Gitee]](https://gitee.com/open-hand/devops-service) - - DevOps Service is the core service of Choerodon. Integrated several open source tools to automate the process of planning, coding, building, testing, and deployment, operation, monitoring.

- **gitlab-service** [[GitHub]](https://github.com/open-hand/gitlab-service)|[[Gitee]](https://gitee.com/open-hand/gitlab-service) - The service interacts with Gitlab by introducing an external Java client. This client handles Gitlab requests from other services by directly invoking the API provided by Gitlab.

- **workflow-service** [[GitHub]](https://github.com/open-hand/workflow-service)|[[Gitee]](https://gitee.com/open-hand/workflow-service) - The Activiti7-based workflow service enables dynamic and flexible creation, initiation, monitoring and management of processes.

- **agile-service** [[GitHub]](https://github.com/open-hand/agile-service)|[[Gitee]](https://gitee.com/open-hand/agile-service) - The service is responsible for Agile process management and the core service of the Porkfish platform. Its main functions include agile process management, including issue management, to-do items, release versions, active sprints, module management, reporting, etc.
- **test-manager-service** [[GitHub]](https://github.com/open-hand/test-manager-service)|[[Gitee]](https://gitee.com/open-hand/test-manager-service)  - The service is a test management module for Choerodon. Its main functions include test case management, test cycle, test report analysis, automated testing, etc.
- **knowledgebase-service** [[GitHub]](https://github.com/open-hand/knowledgebase-service)|[[Gitee]](https://gitee.com/open-hand/knowledgebase-service) - This service is Choerodon's knowledge management module. Its main functions include creating knowledge, editing knowledge, navigation, linking, searching, and so on.

- **code-repo-service** [[GitHub]](https://github.com/open-hand/code-repo-service)|[[Gitee]](https://gitee.com/open-hand/code-repo-service) - The service is a code base management module that provides functions such as authority management through integration with Gitlab, through the Choerodon platform one-stop management of the code base.
- **prod-repo-service** [[GitHub]](https://github.com/open-hand/prod-repo-service)|[[Gitee]](https://gitee.com/open-hand/prod-repo-service) - This service is a product library module that integrates With Nexus and Harbor to provide management of Maven packages, NPM packages, Docker images, etc.

- **choerodon-ui** [[GitHub]](https://github.com/open-hand/choerodon-ui)|[[Gitee]](https://gitee.com/open-hand/choerodon-ui)  - An enterprise-class UI design language and React-based implementation.Realize the react component of Material Design  of Google based on Ant Design Components , which is used to develop and serve the enterprise level back-end products.
- **choerodon-front** [[GitHub]](https://github.com/open-hand/choerodon-front)|[[Gitee]](https://gitee.com/open-hand/choerodon-front)  - The project is an overall front-end project that combines Choerodon base, Choerodon devops Choerodon agile, etc.
- **choerodon-front-hzero** [[GitHub]](https://github.com/open-hand/choerodon-front)|[[Gitee]](https://gitee.com/open-hand/choerodon-front)  - This front-end service is the front-end service of Partial functions transplanted to HZero system after the fusion of Choerodon and HZero, including user management, interface, API testing and other functions.
- **choerodon-cluster-agent** [[GitHub]](https://github.com/open-hand/choerodon-cluster-agent)|[[Gitee]](https://gitee.com/open-hand/choerodon-cluster-agent) - It is a core component of the continuous delivery of Choerodon, deployment pipeline through active connections, and interacting directly with Kubernetes clusters, such as cluster status checks, application environment status checks, updates, and more.

## Demo environment

And you can also experience [the demo environment of Choerodon](https://choerodon.com.cn/#/base/register-organization).

## Contribute

We welcome your input! If you have feedback, please [submit an topic](http://forum.choerodon.io/). If you'd like to participate in development, please read the [documentation of contribution](CONTRIBUTING.md) and submit a pull request.

## Support

If you have any questions and need our support, [reach out to us one way or another](http://choerodon.io/zh/community/).
