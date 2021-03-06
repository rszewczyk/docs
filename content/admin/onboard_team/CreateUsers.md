<!--
title: "Create Users"
description: "Creating Users in Contrast TeamServer"
tags: "Admin onboarding TeamServer user settings license defend protection create"
-->

Users can be created by the System Administrator, as well as by the Organization Administrator. All users created in Contrast will be required to have a default organization and a default role within that organization. Users currently need to be added to Contrast one user at a time unless integrated with [Active Directory](installation-setupauth.html#ad) or [LDAP](installation-setupauth.html#ldap).

## Creating Users as a System Administrator

* Log in to Contrast 
* Navigate to the user menu in the upper right 
* Select **SuperAdmin** in the "Use Contrast Security as:" section
* Select **Users** from the top navigation
* Click the **Add User** button
* Provide the required inputs (Email, First & Last Name, default Organization and Organization Role) 

>**Note:** Make sure you verify the [Role](admin-manageorgsroleperm.html#roles) so that users will have the privileges to carry out the actions you intend.

You can set the user up with a password or invite users to join via a required email activation. Once added, their status will be displayed on the main Users page to identify who is waiting activation, active/inactive, or is locked out of their account based on security policy. 

You may decide to designate an [Application Access Group](admin-onboardteam.html#group) which can provide more administrative function for an application or restrict what applications the user can view or modify.

Enterprise On-Premises (EOP) customers have the ability to delegate users to perform system administration functions across organizations such as managing users, groups, applications, licenses, API keys and security policies. This assumes multiple organizations have been created within Contrast as part of a multi-tenant deployment. See [Granting and Revoking SuperAdmin Permissions](admin-manageorgs.html#sa) to get started.

## Creating Users as an Organization Administrator

1. Log in to Contrast
2. Navigate to the user menu in the upper right 
3. Select **Organization Settings**
4. Select **Users** in the left navigation
5. Click the **Add User** button
6. Provide the required inputs (Email, First & Last Name, and default Organization Role)

>**Note:** Make sure you verify the [Role](admin-manageorgsroleperm.html#roles) so that users will have the privileges to carry out the actions you intend.

<a href="assets/images/Create_User.png" rel="lightbox" title="Add User"><img class="thumbnail" src="assets/images/Create_User.png"/></a>

Users will receive an activation email to join Contrast. You will be able to check their status from the main Users table to identify who is waiting activation, active/inactive, or is locked out of their account based on security policy.

You may decide to designate an [Application Access Group](admin-onboardteam.html#group) which can provide more administrative function for an application or restrict what applications the user can view or modify.

For more information, read about how to [Manage Users](admin-manageorgs.html#manage-user). 

