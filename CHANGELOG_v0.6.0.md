# Changelog
All notable changes to Choerodon framework, DevOps and Agile will be documented in this file.

## Choerodon framework
### [0.6.0] - 2018-06-10
### Added

#### 0.6.0 Significant added features

- Added root administrators to manage the settings of the platform and all organizations and projects in the platform.
- Added new users to modify avatars, usernames, and emails. The user's personal center page is optimized.
- Added microservice routing management function for visual management of backend routing of microservices.
- LDAP supports custom user attributes, adds page test connectivity, and synchronizes user functionality. Currently, it supports both OpenLdap and Microsoft Active Directory directory types.
- The page adds a delete confirmation prompt to reduce the chance of accidental deletion.
- The code library adds automation scripts for circle ci.
- The authentication service adds redis as a storage login session, which is used to guarantee the user session when the authentication service starts multiple instances.

#### Control 0.3.1

- New Select component loading property, can be set to loading state when obtaining asynchronous data.
- Added IconSelect component, drop-down page showing all icon icons.

#### boot0.6.0

- Added port configuration, default 9090.
- Added 403 pages, Page component added service attribute, Function same Permission, No privilege displayed 403 page.

#### Framework dependency 0.5.1

- Added choerodon-websocket-helper dependency, which was updated from choerodon-socket-helper. It mainly provides message route forwarding for Websocket, and implements command-interaction between devops-service and choerodon-agent.
- Added the choerodon-gitlab4j-api dependency, which mainly modifies the gitlab api java client to support the interaction between gitlab-service and gitlab.


## Choerodon DevOps
### [0.6.0] - 2018-06-10
### Added
- `Release management` section, including `application release` and `application market`. 
- Service/Ingress status, operation type and status in `service` and `ingress` to track their running conditions.
- `Container log` in `container` to track its running status. 
- Review function in `application deployment` for users to check their operation. 
- Comments in `configuration information` to remind users when they edit the values files. 
- Upgrade reminder of env-agent in `environment pipeline`. 
- Commit link to Gitlab in tag list in `branch management`. ­­­
- Page height and table column width auto adaption for a better user interface. ­­­­­­
- Resource consistency mechanism in env-agent.
- Message sending failure and timeout confirmation mechanism in env-agent. 

### Changed
- Reconfigure `application deployment`, delete instance query and add `application instance`. 
- Distinguish Service domestic port and target port in `Service`.
- Change the way of `application deployment` from vertical steps to horizontal steps.
- Design a more intuitive and concise `application instance` for a better user experience.
- Update three predefined `application templates` to be more useable. 
- Improve the way of replacing values and the yaml theme color in `configuration information` for a better user experience.
- Modify some APIs based on the more standardized naming rule. 
- Reconfigure gitlab-service to change the way of value passing. 
- Optimize the instance scan mechanism.

### Removed
- "Rapid Deployment" functionalities.

### Fixed
- Logical bug in version check and error shown in frontend in `branch management`. 
- Failure to acquire code from source code repo caused by double slash in url. 
- Paging failure in `branch management`.
- Inconsistent status after devops-service and env-agent restart.
- Orgnization admin not in Gitlab template group.
- Some other bugs.

## Choerodon Agile
## [0.5.0] - 2018-06-10
### Added
- In issue list managerment interface.Users can query and sort issue by dimensions such as type, number, summary, priority and status.
- In issue detail management view.Users can paste static and dynamic images in the description of the issue detail,and large-screen view of the picture is supported.At the same time, the file of the issue and other attachments can be uploaded in the issue detail.
- Time estimation control functionality enables users to control the progress of this issue by using story points and remaining time.
- The multi-dimensional issue management functionality. Users can to manage issues in compinents,fixed versions,labels, epics and sprints.
- The multi-dimensional issue management functionality.Management types include five categories: epic, story, task, bug and sub-task.
- Issue comment functionality. Users can comment and facilitate the discussion issue in issue details.
- Issue log recording functionality.Users can dynamically record the progress of the issue processing, and deduct the remaining time of the issue according to the time recorded in the log.
- Issue sub-task functionality.Users can create and manage sub-tasks in the detail of the issue. Issues can be managed in a more detailed way by splitting into sub-tasks.
- Issue quick creation functionality.To create an issue,users only need to select the corresponding type and fill out the issue brief information.
- Sprint management functionality.Users can create, enable,close current active sprint.Also you can define the sprint start and end time,name and other information.You can view in the sprint detail the current assignment of the issue among corresponding sprint memers and the corresponding remaining time.
- Problem scheduling functionality.Users can drag and drop the issues in the workbench to the required epic or version through single-selection and multi-selection drag and drop. You can also drag and drop into a certain sprint, reflected in the sort of position priority. It also supports issue quick creation in to-do list view.
- Epic management functionality.Users can quickly create epics on the workbench.You can drag and drop the epic of the issue and filter issues by epic.
- Version management functionality. Users can quickly create a version on the workbench.You can drag and drop the version of the issue and at the same time you can filter issues by version as well.
- Multi board management functionality.Users can create multiple boards. Different boards can define different lane processes and split project management into multiple board processes according to different requirements.
- Board configuration management.Users can define board flow according to their own needs, swim lane status,etc.
- Active sprint issue filtering functionality.Currently support issue filtering in two dimensions including “my issues” and “user stories”.
- Active sprint time tracking functionality.Users can track the progress of the current issue and the remaining time of the sprint on board.
- Active sprint issue management functionality.Users can drag and drop the issue on board.The status of the issue will be based on the operation of the corresponding flow.It also supports the sub task of lane management.
- Version management list view functionality.Users can view version management in the form of table,edit, delete, publish and cancel publish version.
- Version detail interface.Users can view all the issues in this version and all related issues in this interface.
- Version release functionality.Users can publish version and choose to migrate unfinished issues to other unreleased versions.
- Component management view functionality.Users can create, edit and delete a component.It also supports multi-field sorting and filtering functions in list view.
- Users can define the default handler strategy using template.
