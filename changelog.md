# Release Notes

### 1.5 (July 5, 2021)

* Added new fields for registration an organization on the server

### 1.8 (August 23, 2021)

* Desciption__c field added to Deployment__c object.
* New Deployment Wizard UI updated with new Description field. First step renamed to Deployment Name, second step - Source.
* New default actions added: Execute Anonymous Apex and Profile Update.
* Deployment UI updated with notifications when Execute Anonymous Apex or Profile Update actions have empty bodies.
* Removed unused old resources.
* Fixed issue with PostInstall script.

### 1.9 (September 8, 2021)

* Added hints for Home, Organizations and Deployments tabs. Added hint for Deployment page.
* Added the following sections to the Home tab: FieldSets, Field History Tracking, ListViews, HelpTexts.
* Added Zuppio Package ‘How to Start?’ section to Documentation on the Home tab.
* Compressed images in static resources.
* Updated loading process of the Home tab.
* Updated Organizations and Deployments tabs to show ‘empty’ pictures and short comment for empty lists.
* Updated Authorization button disabling condition on Organizations tab.
* Fixed section names in Documentation on Home page.
* Fixed typos.
* Fixed checkbox selection in Actions section in Deployment.
* Fixed checkbox selection in Targets section in Deployment.
* Fixed error handling on the Home tab.
* Fixed Profile Update details view.
* Fixed revert modal positioning and closing with the Escape button.
* Fixed Org Id display on the Organizations tab.

### 1.10 (September 16, 2021)

* Added ‘Add Organization’ and ‘Add Deployment’ buttons to the Home tab.
* Added a glowing effect to several buttons on the Home, Organizations and Deployments tabs to attract attention in several cases.
* Added new documents to ‘How to start’ Documentation section.
* Added links to Salesforce articles into the ‘Supported components’ section of Documentation.
* Updated Documentation section view.
* Updated documentation opened from help texts by click (Create New Deployment and Create New Action wizards).
* Fixed text area label in New Action wizard.

### 1.11 (September 20, 2021)

* Renamed Deployment to Job.
* Renamed Action to Step.
* Added documentation on ‘How to create step’ for each feature.

### 1.12 (October 13, 2021)

* Updated New Job Wizard: removed Targets and Steps sections.
* Updated documentation related to new Job creation.
* Updated Job loading sequence to remove long time to wait before table renders.
* Updated label for package selection in New Job wizard.
* Updated Job view: added new 'No records' texts, icon for cancelled deploy.
* Updated Profile Update step creation process: added option to choose Profiles and option to copy the configurations related to the managed package from source to target orgs.
* Updated documentation related to Profiles.
* Updated Profiles log view in history log.
* Updated errors view in history log.
* Fixed issue with not blocked ‘Previous’ button when editing step.
* Fixed issue with navigation back and forward when creating new step.
* Fixed issue with ability to save Execute anonymous step with empty body.
* Fixed issue when New Job wizard modal was not cleared after closing.
* Fixed issue with incorrectly closing report window on Esc press (when History details viewed).
* Fixed issue with Execute anonymous debug copy in history log.

### 1.13 (October 29, 2021)

* Added User name to the Organizations tab.
* Added Search by org name, org Id and user name on the Organizations tab.
* Added navigation between ZuppIO Navigator tabs.
* Added search functionality by org name, org Id and user name to Select Source input in the New Job wizard.
* Added search functionality to the Edit Targets List form in Job view.
* Added search functionality to the Jobs tab (by job name, package name and source org name).
* Updated organization validation logic to save/update username on completion.
* Fixed issue with missing spinner on target list saving (from Job view).
* Fixed issue missing authorization error status on targets list (in Job view).
* Fixed issue when ‘Open in browser’ button was enabled on target with authorization errors (from Job view).

### 1.14 (November 11, 2021)

* Added ‘Unauthorized Hub Members’ section for EnvironmentHubMember records to the Organizations tab.
* Added ‘Block updates’ and ‘Hide from the list’ options to organizations on the Organizations tab.
* Updated Source orgs combobox in New Job wizard (added error and info status icons, blocked orgs with auth errors).
* Updated ‘Edit Targets List’ section to show unauthorized hub members, but exclude hidden and marked as blocked for updates.
* Updated error handlers.

### 1.15 (November 11, 2021)

* Fixed logic to obtain Name from the standard EnvironmentHubMember records.

### 1.16 (December 31, 2021)

* Added ‘Request Access’ feature.
* Added 'Zuppio Settings' tab.
* Added mass select functionality (by pressing Shift and clicking the left mouse button) in the dual list box component (Hide organization view, Edit Targets List view, New Step view).
* Added ‘Hidden’ and ‘Blocked for updates’ orgs number to the Home tab.
* Added total orgs number per section to the Organizations tab.
* Removed ‘Username’ column and sorting by status from ‘Unauthorized Hub Members’ section on the Organizations tab.
* Fixed spinner on Organizations and Jobs tabs loading.

### 1.17 (March 24, 2022)

* Added support for 2nd generation packages.
* Added ‘Package Upgrade’ feature.
* Added support for LMA Organizations.
* Added documentation related to ‘Package Upgrade’.
* Added organizations visibility feature. Now you are able to make authorized organizations private and public using sharing settings.

### 1.20 (March 24, 2022)

* Fixed LMA processing logic, UI display improved.
* Performance improved.

### 1.21 (March 31, 2022)

* New Feature: Profiles deployment by properties (i.e. Field permissions, RecordType visibilities, etc. can be deployed on demand).
* New Feature: steps ordering inside jobs.
* New Feature: enable/disable Environment Hub Members and LMA Organizations sections in Organizations tab.
* New Feature: Zuppio Logs. Added a new tab containing all time history statistics grouped by jobs.

### 1.22 (June 20, 2022)

* New Feature: ‘Zip Packages’ feature.
* New Feature: create job without source org and package.
* New Feature: edit job.
* Renamed Authorized Hub Members to Authorized Organizations.
* Added documentation related to ‘Zip Packages’.
* Added documentation related to ‘Order of the Steps execution’.
* Added documentation related to ‘What is 'On Error' action.

### 1.23 (June 24, 2022)

* New Feature: choose which tests to run in ‘Zip Packages’. 
* New Feature: added ‘Create & New’ button to the New Step.

### 1.24 (July 6, 2022)

* New Feature: edit job name. 
* Added workaround for know issue with apex not compiling when instal or update package.

### 1.25 (August 5, 2022)

* New Feature: clone step.
* New Feature: clone job.
* New Feature: CI/CD.
* New Feature: ‘Compact Layout Assignments’ deployment.
* New Feature: ability to manually run job synchronization with Source Org (Required if package version was updated in source org).

### 1.26 (August 12, 2022)

* Improvements: Jobs UI update.

### 1.27 (September 16, 2022)

* New Feature: git webhooks support for CICD.
* New Feature: authorization quick action (Organizations tab).
* Logs update: each record can be accessed via url directly.
* Jobs update: each record can be accessed via url directly.

### 1.28 (September 20, 2022)

* Improvements: New Step CICD UI update.

### 1.29 (November 8, 2022)

* New Feature: Protected Components.
* New Feature: org authorization by instance url.
* Jobs update: show warning if source org has problem with authorization.

### 1.30 (December 8, 2022)

* Fixed reauthorization of the organization. 
* Fixed check valid xml code when create new step with Profile Update type.

### 1.31 (December 15, 2022)

* Added ‘Monthly Usage’ section to the Home tab.
* New Feature: rename step.
* Jobs update: Added validation of the name when creating or updating steps.

### 1.33 (January 5, 2023)

* Fixed authorization detail check.

### 1.34 (February 15, 2023)

* New Feature: Abort Job.
* New Feature: Manual set picklist values config for Picklist values.
* New Feature: Copy Active/Inactive status for Picklist values.
* New Feature: ‘Record Type’ feature.

### 1.36 (April 18, 2023)

* Fixed sorting in tables.
* Added the ability to validate the organization's creds, which are marked as Reauthorization needed.

### 1.38 (July 20, 2023)

* Performance improved.
* A correction has been made to the text on the Home page.
* Added the ability to perform package update with packages that have a password for installation.
* An edit was made to display the total number of the organization.

### 1.39 (December 22, 2023)

* Performance improved.
* Minor UI fixes.
* Stability improvements.

### 1.40 (January 25, 2024)

* Performance improved.
* Fixed task ordering after copying jobs.
* Fixed saving xml code when creating a task with Profile Update types.

### 1.41 (December 30, 2024)

* Performance improved.
* Fixed the display of the modal window when creating a request for access to the organization.
* Added the display of detailed information about the request and a link to access the organization.