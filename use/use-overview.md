# Overview

Using the Sunbird Lern components:

**Batch Service**

The Batch Service APIs depend on the content-service APIs provided by the SB Knowlg building block (for content consumption details) as well as the SB Lern UserOrg APIs (for details of the users in the batch). There are also additional dependencies on SB Knowlg as well as the Druid Service in SB Obsrv

\
**Groups**

The Groups Service component has a dependency on the UserOrg component as well as the SB Knowlg building block

Member details in a group are fetched using the User Org service, and addition of activities requires use of the content-service component from the SB Knowlg BB

**Discussion Forum**

The discussion forum component does not have any other cross dependencies, and can be installed independently

**Notification Service**

The Notification Service component can be installed independently, and used to send Email/SMS/FCM and feed/in-app notifications synchronously or asynchronously

**User & Org Service**&#x20;

The UserOrg component can be installed independently.&#x20;

Note: The User update API has a cross building-block dependency Sunbird Ed. It uses the Sunbird Ed form API for user type as well as location type validation, for use cases specific to SB Ed. An adopter can choose to address this dependency on SB Ed by setting up the Form API configs as per their needs and workflows.

\
_<mark style="color:orange;">**Note :**</mark> For developer installation and setup of individual lern components pls refer to_ [_https://lern.sunbird.org/use/developer-installation_](https://lern.sunbird.org/use/developer-installation)





> Please refer to the [Sunbird-Ed deployment ](https://ed.sunbird.org/use/prerequisites-for-your-own-sunbird-ed-instance)for more details on deployment

The deployment view diagram shown below explains how the Lern Building block components are deployed in SunbirdEd.

![](<../.gitbook/assets/Deployement  Diagram (5).png>)
