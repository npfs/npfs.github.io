---
layout: default
title: NPFS Admin Portal Training

---
# Admin Portal



## Contents

**[Getting Started](#getting-started)**

  * [Login Screen](#login-screen)
  * [Select Your User Role](#select-your-user-role)

**[Bulk Load Users](#bulk-load-users)**

  * [CSV Creation](#csv-creation)
  * [CSV Upload](#csv-upload)

**[User Management](#user-management)**

  * [Create A New Account](#create-a-new-account)
  * [Managing a Subordinates Account](#managing-a-subordinates-account)
  * [Manage Account Details](#manage-account-details)
  * [Manage Roles and Access](#manage-roles-and-access)
  * [Manage Password - Reset](#manage-password---reset)
  * [Manage Password - 2 Factor Authentication](#manage-password---2-factor-authentication)

**[System Configuration](#system-configuration)**

  * [Environment Settings](#environment-settings)

**[Collection Point Upload](#collection-point-upload)**

  * [CSV Creation](#csv-creation)
  * [CSV Upload](#csv-upload)
  * [Known Issues](#known-issues)





## Getting Started

Open this link to access the NPFS Admin Portal [www.nationalpandemicfluservice.nhs.uk/admin](https://www.nationalpandemicfluservice.nhs.uk/admin).  It may be advisable to create a bookmark if you will access the application frequently.

At any time you can safely use the **training** system to become familiar with the functions of the live system.  Any actions you take will not be reflected in the live system and you will have no impact on services or patients. [training.nationalpandemicfluservice.nhs.uk/admin](https://training.nationalpandemicfluservice.nhs.uk/admin)


### Login screen

Enter your unique Username and Password.  These will be supplied by your Team Leader.

![][admin-login]

> Your password must be changed at the first login.  Full instructions are provided later in this guide.
>
> Your account will be locked out after 3 unsuccessful login attempts.  Your Team Leader will need to reset.


In order to discourage easy-to-guess passwords, the new password must either be a passphrase (preferred) or it should meet the following complexity requirements:

> The password must be at least 10 characters long.
>
> The password must contain at least one uppercase letter.
>
> The password must contain at least one number.
>
> The password must contain at least one special character.


### Select Your User Role

You may have multiple roles available.  Select the most appropriate role for the tasks that you need to complete.

![][admin-role-screen]

> **Your Session** -  Confirms the username and role you are currently logged in as, as well as your login time and role once you have selected it.
>
> **Logout** - Displayed on all screens, click here to logout of system


## Bulk Load Users

![][admin-bulk-load]

### CSV Creation

* Instruction and required fields for a bulk upload CSV are stated on the page
* Accounts that you create using this function will be added immediately for you to manage.
* Download the template to ensure correct format is used (see below)
* SCAS to insert guidance on distribution of account details to subordinates
* A maximum of 1,000 user accounts can be created per csv file

![][admin-bulk-load-template]


### CSV Upload

* Use the **Browse** button to locate your saved .CSV file
* Click **Upload File** to carry out the Bulk Load
* A message box will appear to confirm the results of the bulk load
* Any errors will be identified here, along with the cause of the failure
* An example failure record is shown here

![][admin-bulk-load-errors]



## User Management

![][admin-user-management]

### Create A New Account

![][admin-user-search]

* Click **Create new user**
* Complete necessary account details (Username, First Name, Surname, etc.) on **Account Details** tab
* Select a role / roles to add using **Roles** tab - setting start and end date of role if known
* Enter a **Temporary Password** for the account using the **Password** tab

SCAS are responsible for the distribution of passwords and account details, making use of secure nhs.net e-mails to transfer

![][admin-user-create-details]

> All tabs that contain mandatory fields must be completed before save button is enabled


### Managing a Subordinate's Account

* Select **User Management** in the Admin home screen
* You can search for all subordinates you manage by entering some of their details in the search bar and clicking on the magnifying glass
* Search works on name, surname, username or organisation.
* Select the user whose account you wish to change / manage using the radio button on screen
* Click **Continue**
* Only users set-up as your subordinates are manageable by you, you cannot edit your own permissions or those of people whose accounts you do not manage

![][admin-user-search-results]


### Manage Account Details

* **Account Details** tab
* The selected users account details are displayed
* Here you can edit any of these details, then click on save.
* **Notice** tab
* This allows you to insert a pop-up notice the user will see every time they log on to the system (e.g. could link to a policy document / reminder of a specific working practice)
* This is a free text field so can you can decide whether you wish to use this feature or not.


### Manage Roles and Access

* **Roles** tab
* Here you can add or remove roles for a person you manage
* Click on the **bin** icon to delete a role
* Click on the **pen** icon to edit the role (e.g. amend start / end date)
* Click on the **plus** icon to add a new role
* Select the role you wish to add from the drop down list and complete the required details.
* Once you click on save this will be immediately added to your subordinates list of available roles.
* Click on **Manage Password** to reset or change the password of a subordinate


### Manage Password - Reset

* If a subordinate has forgotten their password or locked themselves out by entering it 3 times incorrectly you will need to carry out a password reset
* Select **Reset Password** and enter a Temporary Password that complies with the stated guidelines
* Click **Submit** to complete the reset
* You must inform the subordinate of the reset password in a secure manner

SCAS are responsible for the distribution of passwords and account details, making use of secure nhs.net e-mails to transfer


### Manage Password - 2 Factor Authentication

![][admin-user-two-factor]

* Two-Factor Authentication can be set up for any user by their manager.
* It creates a safe login mechanism (instead of a fixed password) which requires a user to enter a set PIN + a 6 digit code generated by the Authentication Application.
* User will need to ensure they have an Authenticator App installed on their smart phone - search for "Google Authenticator" in the relevant application store for their smartphone (Apple / Andriod / etc.)
  * Type begin setup
  * Scan barcode / enter key on screen
  * They must now use 2-factor authentication to log in (their PIN + 6 digits generated by Authenticator App) instead of a password
* To set up 2-Factor Authentication on an account follow the steps on this screen
* You must ensure the user whose account you are editing is with you and inputs their own Secret Key and PIN.
* Click Submit to complete setting up 2-Factor Authentication for the user
* Use Back to return to User Management screen


## System Configuration

![][admin-system-config]

### Environment Settings

* This is where the various NPFS environments - including live - are managed
* This element of the Admin Portal is restricted to very limited, high privileged users from the Command & Control and NHS Digital DevOps teams


## Collection Point Upload

![][admin-collection-point-upload]

### CSV Creation

* This is where the Collection Point information is managed (i.e. active collection points and their associated details)
* This element of the Admin Portal is restricted to very limited, high privileged users from the Command & Control and NHS Digital DevOps teams


### CSV Upload

* This is where the Collection Point information is managed (i.e. active collection points and their associated details)
* This element of the Admin Portal is restricted to very limited, high privileged users from the Command & Control and NHS Digital DevOps teams


### Known Issues

* IE8 & IE9 - behaviour is not consistent with design, recommended that users access the Admin portal using Chrome or Firefox until IE issues are resolved




[login-screen]: images/login-screen.jpg "Login Screen"
[role-screen]: images/role-screen.jpg "Role Screen"
[admin-login]: images/admin-login.png "Admin Login Screen"
[admin-role-screen]: images/admin-role-screen.png "Admin Role Screen"
[admin-collection-point-upload]: images/admin-collection-point-upload.png "Admin Collection Point Upload Icon"
[admin-bulk-load]: images/admin-bulk-load.png "Admin Bulk Load Icon"
[admin-bulk-load-template]: images/admin-bulk-load-template.png "Admin Bulk Load Template"
[admin-bulk-load-errors]: images/admin-bulk-load-errors.png "Admin Bulk Load Errors"
[admin-system-config]: images/admin-system-config.png "Admin System Config Icon"
[admin-user-management]: images/admin-user-management.png "Admin User Management Icon"
[admin-user-create-details]: images/admin-user-create-details.png "Admin User Create Details"
[admin-user-search]: images/admin-user-search.png "Admin User Search Box"
[admin-user-search-results]: images/admin-user-search-results.png "Admin User Search Results"
[admin-user-two-factor]: images/admin-user-two-factor.png "Admin User Two Factor"

