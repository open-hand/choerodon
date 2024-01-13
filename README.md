English | [简体中文](./README_zh.md) | [Home](https://zknow.com/choerodon/) | [Documents](https://support.yqcloud.com/#/knowledge/public/407850582201335808/web_c7n?tenantId=228549383619211264&version=V2.0.0&menu=space&spaceId=407850582201335808) | [Blog](https://zknow.com/choerodon/blog/choerodon-name/) | [Community](http://choerodon.io/zh/community/) · [Forum](https://openforum.hand-china.com/c/33-category/33) | [Cases](https://zknow.com/choerodon/classic) | [Screenshots](https://github.com/choerodon/choerodon/blob/master/SCREENSHOT.md) | [Roadmap](https://github.com/choerodon/choerodon/blob/master/ROADMAP.md) | [Release Notes](https://github.com/choerodon/choerodon/blob/master/changelogs/)


Tips: We welcome your input! If you have feedback, please [submit an topic](https://openforum.hand-china.com/c/33-category/33) in [the forum of Choerodon](https://openforum.hand-china.com/c/33-category/33).

And you can also [sign up Choerodon](https://choerodon.com.cn/register-organization/#/) and kickstart your journey.

# Choerodon - Open source whole value chain multi-cloud agile collaboration platform

![](img/choerodon-community.png)

Choerodon is an Open source whole value chain multi-cloud agile collaboration platform, which is built on open source technologies, including [Kubernetes](https://kubernetes.io/), [Istio](https://istio.io/), [knative](https://pivotal.io/knative), [Gitlab](https://about.gitlab.com/) and [Spring Cloud](https://spring.io/projects/spring-cloud), to enable integration of local and cloud environments and achieve the consistency of enterprise cloud/hybrid cloud environments. By providing Lean-Agile, continuous delivery, container environments, microservices, DevOps, and other capabilities, the platform helps organizations to manage applications lifecycle, and deliver business value rapidly and frequently.


Choerodon provides:

- A comprehensive tool chain supporting DevOps best practices, supporting Scrum management from planning, programming, building, testing, publishing, and operations.

- A suite of Spring Cloud-based microservice application frameworks to help companies become faster and more efficient for microservice development.

Choerodon 2.0: Open source with new capabilities for greater availability and stability! Choerodon 2.0 brings new capabilities for open source code management, artifact library management, CI/CD pipeline, container management, environment resources, application deployment, and more to provide greater availability and stability. Although this release does not include project management, test management, knowledge base etc. you can sign up for a trial environment to experience the project collaboration management features.

It should be noted that Choerodon CE 2.0 does not support upgrades from v1.1. However, we sincerely hope that you can install Choerodon CE 2.0 and experience the excellent performance and functionality brought by Choerodon 2.0. Looking forward to your participation and feedback!

Choerodon 2.0 brings you a brand new open source experience! 

## The feature of Choerodon 
  
- [**Collaboration(Enterprise Edition)**](https://zknow.com/choerodon/#cooperation) - Combine Lean-Agile to manage business requirements and tasks to create an efficient collaborative ecosystem. Provides collaboration tools such as worklist, story map, and knowledge management. It is a value chain that runs through development, test, and deployment. It promotes communication among team members, reduces project management costs, and improves communication and collaboration efficiency.

- [**Development**](https://zknow.com/choerodon/#development) -Provides an iterative planning and continuous integration pipeline to help standardize application service development and achieve rapid iteration. Guided by the concept of DevOps, combined with lean Kanban and Gitlab branch management, it provides a continuous integration pipeline, shortens the development cycle of application services, improves team efficiency, and efficiently and frequently delivers new software versions to test teams or users.

- [**Deployment**](https://zknow.com/choerodon/#deploy) -Pipelined multi-environment one-click deployment. Users can easily use the deployment function to manage various application services developed and deployed using Choerodon, including application start and stop, status monitoring, and version control corresponding to application service, container management and so on, as well as includes various involved resources management in application services, such as network, domain name, database service, cache service, etc.

- [**Test(Enterprise Edition)**](http://choerodon.io/zh/docs/user-guide/test/) -Agile continuous testing tools can effectively improve the efficiency and quality of software testing.Test Management provides users with an agile continuous testing tool, including test case management, test loop, test analysis and so on, which can effectively to improve the efficiency and quality of software testing, improve the testing flexibility and visualization level, and ultimately reduce test time and enable Users focus on building software functions.

- [**Operation**](http://choerodon.io/zh/docs/user-guide/report/) -Various reports that auxiliary the management of the project are collected, and display project progress details and problems in multiple dimensions. Contain agile reports (cumulative flow diagram, burndown chart， etc.), DevOps reports (code submission chart, code quality chart, etc.), test report.

- [**Microservice framework**](http://choerodon.io/zh/docs/development-guide/) - Microservice framework based on microservice technology platform hzero,with this development framework user can easily build application services.

Also, you can view the [screenshots of Choerodon](SCREENSHOT.md) to have a most intuitive understanding of Choerodon, and you can visit the website of Choerodon [choerodon.io](https://zknow.com/choerodon/)

## Component relationship list
```
└─ choerodon-parent                                CHOERODON parent
    ├─ choerodon-register                                eureka server
    ├─ choerodon-gateway                                 gateway service
    ├─ choerodon-swagger                                 swagger service
    ├─ choerodon-admin                                   platform administration service
    ├─ choerodon-oauth                                   oauth service
    ├─ choerodon-iam                                     iam service
    ├─ choerodon-platform                                platform management
    ├─ choerodon-file                                    file service
    ├─ choerodon-monitor                                 monitor service
    ├─ choerodon-message                                 message service
    ├─ devops-service-business                           devops service
    ├─ workflow-service                                  workflow
    ├─ gitlab-service                                    gitlab service
    ├─ hrds-prod-repo                                    production repository service
    ├─ hrds-code-repo                                    code repository service
    ├─ hzero-parent                                      hzero parent
    └─ choerodon-starter-parent                          common develop dependency parent
        ├─ choerodon-gitlab4j-api                             choerodon gitlab api
        ├─ choerodon-tool-liquibase                           liquibase initialization tool 
        │  └─ hzero-installer                                 hzero initialization tool
        ├─ choerodon-starter-core                             common helper
        └─ choerodon-starter-asgard                           asgard client
```
For detailed component information on HZERO-PARENT，see[HZERO](https://github.com/open-hand/hzero.git).


## Installation
 
Please follow [the documentation of installation](https://support.yqcloud.com/#/knowledge/public/407850582201335808/web_c7n?tenantId=228549383619211264&version=V2.0.0&menu=folder&folderId=444097926325235712) to install Choerodon.

## To start using Choerodon

For operation manual, please read the documentation [choerodon.io](https://support.yqcloud.com/#/knowledge/public/407850582201335808/web_c7n?tenantId=228549383619211264&version=V2.0.0&menu=folder&folderId=444160602170609664).

If you have any questions, you can post in [forum](https://openforum.hand-china.com/c/33-category/33).

## To start developing with Choerodon

There are two parties, **microservice backend** and **frontend**, in Choerodon microservice development framework.


If you want to develop microservice backend, please refer to the   [microservices developer's documentation](https://support.yqcloud.com/#/knowledge/public/407850582201335808/web_c7n?tenantId=228549383619211264&version=V2.0.0&menu=knowledge&knowledgeId=444098186002984960).


Also, with the help of [frontend developer's documentation](https://support.yqcloud.com/#/knowledge/public/407850582201335808/web_c7n?tenantId=228549383619211264&version=V2.0.0&menu=knowledge&knowledgeId=444098189316468736) , you can use the Choerodon`s frontend style.

## The components of Choerodon

This repository contains the source code for Choerodon documentation. If you're looking for individual components, they live in their own repositories.
- **choerodon-starter** [[GitHub]](https://github.com/open-hand/choerodon-starters)|[[Gitee]](https://gitee.com/open-hand/choerodon-starters) - Is a toolkit developed by Choerodon, which provides some of the basic dependencies used in the development process.
- **choerodon-framework** [[GitHub]](https://github.com/open-hand/choerodon-framework)|[[Gitee]](https://gitee.com/open-hand/choerodon-framework) - Choerodon microservices framework.
- **choerodon-register** [[GitHub]](https://github.com/open-hand/choerodon-register)|[[Gitee]](https://gitee.com/open-hand/choerodon-register) - The service Choerodon's Platform registry service is based on Eureka.
- **choerodon-platform** [[GitHub]](https://github.com/open-hand/choerodon-platform)|[[Gitee]](https://gitee.com/open-hand/choerodon-platform)  - This service is Choerodon as the basic management service of the platform, mainly providing some basic capabilities for the platform, such as system configuration, development configuration, etc.
- **choerodon-oauth** [[GitHub]](https://github.com/open-hand/choerodon-oauth)|[[Gitee]](https://gitee.com/open-hand/choerodon-oauth)  - This service is the Choerodon microservice architecture authorization center and is mainly responsible for user permission setting and authorization.
- **choerodon-swagger** [[GitHub]](https://github.com/open-hand/choerodon-swagger)|[[Gitee]](https://gitee.com/open-hand/go-choerodon-swagger)  - This service is Choerodon's API document management service, which is mainly responsible for interface document, API document of platform development test and debugging management.
- **choerodon-gateway** [[GitHub]](https://github.com/open-hand/choerodon-gateway)|[[Gitee]](https://gitee.com/open-hand/choerodon-gateway)  - This service is Choerodon's Spring Cloud Gateway based microservice Gateway service.
- **choerodon-file** [[GitHub]](https://github.com/open-hand/choerodon-file)|[[Gitee]](https://gitee.com/open-hand/choerodon-file)  - The service is Choerodon file management, which provides file storage services for the platform.
- **choerodon-message** [[GitHub]](https://github.com/open-hand/choerodon-message)|[[Gitee]](https://gitee.com/open-hand/choerodon-message)  - The service is Choerodon message management, a unified messaging push portal for the platform.
- **choerodon-admin** [[GitHub]](https://github.com/open-hand/choerodon-admin)|[[Gitee]](https://gitee.com/open-hand/choerodon-admin)  - This service is Choerodon's platform governance service and provides automated routing refresh, authority refresh, swagger information refresh.
- **choerodon-iam** [[GitHub]](https://github.com/open-hand/choerodon-iam)|[[Gitee]](https://gitee.com/open-hand/choerodon-iam)  - This service is the core back-end service of Choerodon, with administrative functions such as user, role, permission, organization, project, password policy, client, menu, icon, multi-language, etc., supporting the import of third-party users through LDAP.
- **choerodon-asgard** [[GitHub]](https://github.com/open-hand/choerodon-asgard)|[[Gitee]](https://gitee.com/open-hand/choerodon-asgard)  - This service is Choerodon's distributed timing task and distributed transaction management service.
- **choerodon-monitor** [[GitHub]](https://github.com/open-hand/choerodon-monitor)|[[Gitee]](https://gitee.com/open-hand/choerodon-monitor)  - This service is Choerodon's audit monitoring service and provides monitoring audit capabilities, including data audit and operational audit.

- **devops-service-business** [[GitHub]](https://github.com/open-hand/devops-service-business)|[[Gitee]](https://gitee.com/open-hand/devops-service-business) - - DevOps Service is the core service of Choerodon. Integrated several open source tools to automate the process of planning, coding, building, testing, and deployment, operation, monitoring.

- **gitlab-service** [[GitHub]](https://github.com/open-hand/gitlab-service)|[[Gitee]](https://gitee.com/open-hand/gitlab-service) - The service interacts with Gitlab by introducing an external Java client. This client handles Gitlab requests from other services by directly invoking the API provided by Gitlab.

- **workflow-service** [[GitHub]](https://github.com/open-hand/workflow-service)|[[Gitee]](https://gitee.com/open-hand/workflow-service) - The Activiti7-based workflow service enables dynamic and flexible creation, initiation, monitoring and management of processes.

- **code-repo-service** [[GitHub]](https://github.com/open-hand/code-repo-service)|[[Gitee]](https://gitee.com/open-hand/code-repo-service) - The service is a code base management module that provides functions such as authority management through integration with Gitlab, through the Choerodon platform one-stop management of the code base.
- **prod-repo-service** [[GitHub]](https://github.com/open-hand/prod-repo-service)|[[Gitee]](https://gitee.com/open-hand/prod-repo-service) - This service is a product library module that integrates With Nexus and Harbor to provide management of Maven packages, NPM packages, Docker images, etc.

- **choerodon-ui** [[GitHub]](https://github.com/open-hand/choerodon-ui)|[[Gitee]](https://gitee.com/open-hand/choerodon-ui)  - An enterprise-class UI design language and React-based implementation.Realize the react component of Material Design  of Google based on Ant Design Components , which is used to develop and serve the enterprise level back-end products.
- **choerodon-front** [[GitHub]](https://github.com/open-hand/choerodon-front)|[[Gitee]](https://gitee.com/open-hand/choerodon-front)  - The project is an overall front-end project that combines Choerodon base, Choerodon devops Choerodon agile, etc.
- **choerodon-front-hzero** [[GitHub]](https://github.com/open-hand/choerodon-front)|[[Gitee]](https://gitee.com/open-hand/choerodon-front)  - This front-end service is the front-end service of Partial functions transplanted to HZero system after the fusion of Choerodon and HZero, including user management, interface, API testing and other functions.
- **choerodon-cluster-agent** [[GitHub]](https://github.com/open-hand/choerodon-cluster-agent)|[[Gitee]](https://gitee.com/open-hand/choerodon-cluster-agent) - It is a core component of the continuous delivery of Choerodon, deployment pipeline through active connections, and interacting directly with Kubernetes clusters, such as cluster status checks, application environment status checks, updates, and more.

## Demo environment

And you can also experience [the demo environment of Choerodon](https://choerodon.zknow.com/register-organization/#/).

## Contribute

We welcome your input! If you have feedback, please [submit an topic](https://openforum.hand-china.com/c/33-category/33). If you'd like to participate in development, please read the [documentation of contribution](CONTRIBUTING.md) and submit a pull request.

## Support

If you have any questions and need our support, [reach out to us one way or another](https://zknow.com/zknow/about/contact-u).
