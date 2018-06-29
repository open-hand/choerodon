# Changelog [中文版](./CHANGELOG_v0.7.0_zh.md)

All notable changes to **Choerodon framework**, **Continuous delivery** and **Agile** will be documented in this file.


## Choerodon framework
### [0.7.0] - 2018-06-29
### Added

#### 0.7.0 Significant added features

- Added `root administrators` to manage the settings of the platform and all organizations and projects in the platform.
- Added new users to modify `avatars`, `usernames`, and `emails`. The user's `personal center` page is optimized.

- Added `microservice routing management` function for visual management of backend routing of microservices.
- `LDAP` supports custom user attributes, adds page test connectivity, and synchronizes user functionality. Currently, it supports both `OpenLdap` and `Microsoft Active Directory` directory types.
- The page adds a delete confirmation prompt to reduce the chance of accidental deletion.
- The code library adds automation scripts for circle ci.
- The `authentication service` adds redis as a storage login session, which is used to guarantee the user session when the authentication service starts multiple instances.

#### Control 0.3.1

- New `Select` component loading property, can be set to loading state when obtaining asynchronous data.
- Added `IconSelect` component, drop-down page showing all icon icons.

#### boot0.6.0

- Added port configuration, default `9090`.
- Added `403` pages, Page component added service attribute, Function same Permission, No privilege displayed 403 page.

#### Framework dependency 0.5.1

- Added `choerodon-websocket-helper` dependency, which was updated from `choerodon-socket-helper`. It mainly provides message route forwarding for Websocket, and implements command-interaction between `devops-service` and `choerodon-agent`.
- Added the `choerodon-gitlab4j-api` dependency, which mainly modifies the gitlab api java client to support the interaction between gitlab-service and gitlab.

### Changed

#### 0.6.0 Significant changed features

- The platform permission check logic is perfect.
- The registry supports service registration for the specified namespace.
- Menu icon replacement, text spacing adjustment.
- Uniform spacing of page icons, adding reminder texts, and button operation prompting copy optimization.

#### Control 0.3.1

- The `Collapse` component modifies the expand and collapse icon styles on the header.
- The `Modal` component adjusts the `footer's button` style. When the button's `loading` state is determined, the cancel button is disabled.
- Table component adjustment, all drop-down boxes inside the component pop up container changes.

#### boot0.6.0

- boot componentized and migrated to npmjs.
- Some component style adjustments.

#### Framework dependency 0.5.1

- `choerodon-starter-tool` sets `is_built_in` to true when routing information is initialized, which means `built-in services`.
- The `customUserDetails` of `choerodon-starter-core` adds the `is_admin` field.

### Fixed

#### 0.6.0 Significant fixed features

- When creating a project under a repair organization, the project code is not unique within the organization, but is a globally unique issue.
- Fixes the issue of removing the user's existing role tag when repairing new role assignments.
- Fixed an issue where the registration center sent an exception and the kafka message did not have a timestamp.
- Fixed an issue where the `manager-service` sometimes failed to refresh.
- Fixed an issue where the menu configuration function under Firefox cannot be used.
- Fixed the problem that members could not be viewed by role in the role assignment.
- Remove the incorrect permission code from the page. This bug will cause the page to fail to have proper permissions.
- In the repair menu configuration, when one self-made directory is placed in another self-directory, the two directories disappear.

#### boot0.6.0

- Fixed issues with Permission and Action components sometimes not working.

#### Framework dependency 0.5.1

- `choerodon-starter-mybatis-mapper` Fixes an exception that occurs when a selectOne query condition matches more than one piece of data.

### Removed

#### 0.6.0 Significant removed features

- Do not remove the word limit in the lower right corner of the page input box.
- The page input box removes auto-fill.

#### boot0.6.0


- Clean up redundant code

## Continuous delivery
### [0.7.0] - 2018-06-29
### Added
- `Application export` section, for exporting applications to other platforms.
- `Application import` section, for importing applications from other platforms.
- `Instance discovery`, `service discovery` and `ingress discovery` section,  for platform self-managing and upgrading.
- `Service management` instanseinstance availability verification.
- `Service management` port legality verification.
- `Ingress management` service availability verification.
- `Ingress management` path address uniqueness verification.
- Predefined roles added for each authorization.
- Settings for Service/Ingress unavailability validation check in `environment` when it is stopped.
- Cancel button added to `application release` and `application deployment`.
- Yaml configuration file check and error information display.
- Chinese and English mode supported.
- Gitlab new version v11.0.1 supported.


### Changed
- Chinese-English translation supported for backend error.
- Two api name changed so as to conform to naming and authority check.
- Optimized predefined application template acquisition for users, manual template creation no longer needed.
- Table column width auto adaption.
- Unified naming standards for table heads in a page.
- Optimized code quality in Ingress management.
- Ingress name unavailable for modification.
- Remove redundant display for identical parts in repository address.
- Relative path used for application icon uploading.
- Optimized application selection display in `application instance` single application interface. Two categories including project application and application market are shown by default. Category list can be expanded.


### Fixed
- Values replacement disorder in application deployment.
- Inaccurate time in Continuous Integration (CI) pipeline.
- Application detail README file unavailability in occasional circumstances.
- Optimized delay caused by multi-step CI request for API.
- Errors in table paging.
- Errors in value filtering when acquiring application versions.
- Optimized prompt information in application version page.
- Absence of "Latest" label for "tag" typed branch in CI pipeline.
- Error in opening "details" link in a new window.
- Inaccuracy in row height yaml calculation when zooming in/out configure information page.
- Unchecked cases when WebSocket component parameters are inadequate. And the resulting failure in connection soon after connection established.

## Agile
## [0.6.0] - 2018-06-29
### Added
- `Issue link` functionality. Users can select link types to link `issue` in issue detail page.When users creating project it will be creating three default types: `blocked`,`duplicate`,`relates`,also it support custom link type in setting functionality.
- `Version archive` functionality. Users can archive the status of a version to archive.
- `Version merge` functionality. Users can cancel archive operation and version status return to the previous status.
- `Sprint report` functionality. Agile service will recorded the statistics of sprint in progress or end. Report include completed issues during sprint, unfinished issues and removed from sprint. After user select the sprint, you can view the report record of this sprint and the simple burn down chart of this sprint.
- `Burn down chart` report of sprint functionality. Agile service will recorded the operational events of the ongoing and end sprint's issues and generates reports and chart information. After user select sprint,statistics on the issues(including subtasks)can be made through the remainng estimated time, story points and issue counts.
- `Custom project code` functionality. Users can modify the code of project in the setting of project in the setting.It's reflected in the issue number after modification.
- `Activity log` functionality.The update operation of issues will be recorded in activity log.Users can view in the details of issues.Sprint statistics are generated from activity log.
- `Custom filter` functionality.Users can create a custom filter in the quick search of the settings.The filter can be configured with fields,types and values.It will be applyed custom filters in issue management view and to-do list view.
- `Board swim lane` setting functionality. Users can set the lanes in the board settings. The lanes can be displayed on activity sprint view based on story, assignee and no.

### Changed

- The `ont-to-one` relationship between `sprints` and `issues` was changed to `many-to-many`.
- Status of created `subtask issue` is the same as parent issue status.
- Supports the removal of `sprints` which status is planning.
- Added `Reports`, `Settings` menu. `Settings` menu contains submenu: `Project Setting`, `Quick Search`, `Issue links`.
- Added permissions for all page view.
- The `epic issue` and version of the `to-do` list view can be displayed on the progress bar if the issue is completed.
- Position the newly created sprint as you create a sprint.
- Users can modify the issue status in the detail of the issue.
- The time selector is accurate to the second.
- Batch selection for `to-do` items supports Ctrl key selection.

### Fixed

- Some users information does not include avatar information.
- Select assignee can only select twenty data.
- `Issue details` anchor monitoring is inaccurate.
- `Issue management view` defect type filter expired.
