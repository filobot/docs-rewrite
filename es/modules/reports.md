# Acerca del módulo

This module will allow you to provide your users with tools to report behavior contrary to the server rules.

> Users or authors of messages that have **Administrator** or **Manage Guild** permissions can't be reported in any case. Also, any exceptions you configure in the module will be applied.
  {.is-info}

> You must be responsible for the data processing of the reports made by users on your server.
  {.is-danger}

> This guide is a hybrid guide, which means that the same steps work for both the **Reports (Member)** and **Reports (Message)** modules.
  {.is-info}

## Set the reports channel

In the select menu, choose the **Set the reports channel** option.

Next, select the channel you want to use for receiving reports. Only **text channels** are supported at the moment.

## Set the ignored role

In the select menu, choose the **Set the ignored role** option.

Next, select the role that users must have in order for reports to be ignored.

## Toggle the deletion of reviewed reports

In the select menu, choose the **Toggle the deletion of reviewed reports** option.

Next, select the option you want to use for the deletion of reviewed reports.

> A report is considered as reviewed once it has been approved/denied by a reviewer.
  {.is-info}

> If you enable deletion of reviewed reports, they will be permanently deleted. This action can't be undone.
  {.is-danger}

## Configure notification roles

All the roles you specify will be pinged once a new report is received, so report reviewers can be aware of new reports submitted by users.

The limit of roles that can be configured is **5 roles**.

### Add notification roles

In the select menu, choose the **Add notification roles** option.

Next, select as many roles as you want to add to the module's notification roles.

> Don't remember if a role is added? Don't worry! We'll filter the roles you select once you have sent us the answer.
  {.is-info}

### Set notification roles

In the select menu, choose the **Set notification roles** option.

Next, select all the roles you want to set in the module's notification roles.

> The previous role list will be replaced using this action. This action can't be undone.
  {.is-danger}

### Remove notification roles

In the select menu, choose the **Remove notification roles** option.

Next, select all the roles you want to remove from the module's notification roles.

> To protect the privacy of our users, some *(or all)* roles may appear with the name **unknown** if they have been deleted from the server.
  {.is-warning}

## Configure the reason parameters

In the select menu, choose the **Configure the reason parameters** option.

### Set the minimum length of member reason

In the select menu, choose the **Set the minimum length of member reason** option.

Next, type in the form the number of numeric *(integer)* characters long that the member reason should be.

> The minimum length of member reason is **0 characters** by default.
  {.is-info}

> The minimum length can't be greater than or equal to the greatest length.
  {.is-warning}

### Set the maximum length of member reason

In the select menu, choose the **Set the maximum length of member reason** option.

Next, type in the form the number of numeric *(integer)* characters long that the member reason should be.

> The maximum length of member reason is **1024 characters** by default.
  {.is-info}

> The maximum length can't be less than or equal to the smallest length.
  {.is-warning}

### Toggle the cleaning of the markdown of member reason

In the select menu, choose the **Toggle the cleaning of the markdown of member reason** option to enable/disable the cleaning of the markdown of member reason.

> Clearing the markdown involves removing all the markdown characters from the member reason such as bold, italic, underline, strikethrough, code, etc.
  {.is-info}

> The cleaning of the markdown of member reason is **enabled** by default.
  {.is-info}

### Set the minimum length of reviewer reason

In the select menu, choose the **Set the minimum length of reviewer reason** option.

Next, type in the form the number of numeric *(integer)* characters long that the reviewer reason should be.

> The minimum length of reviewer reason is **0 characters** by default.
  {.is-info}

> The minimum length can't be greater than or equal to the greatest length.
  {.is-warning}

### Set the maximum length of reviewer reason

In the select menu, choose the **Set the maximum length of reviewer reason** option.

Next, type in the form the number of numeric *(integer)* characters long that the reviewer reason should be.

> The maximum length of reviewer reason is **1024 characters** by default.
  {.is-info}

> The maximum length can't be less than or equal to the smallest length.
  {.is-warning}

### Toggle the cleaning of the markdown of reviewer reason

In the select menu, choose the **Toggle the cleaning of the markdown of reviewer reason** option to enable/disable the cleaning of the markdown of reviewer reason.

> Clearing the markdown involves removing all the markdown characters from the reviewer reason such as bold, italic, underline, strikethrough, code, etc.
  {.is-info}

> The cleaning of the markdown of reviewer reason is **disabled** by default.
  {.is-info}

## Configure the evidences parameters

In the select menu, choose the **Configure the evidences parameters** option.

> We currently only support **Imgur**, **Gyazo**, **YouTube**, and **Discord CDN** as providers for images, videos, or any other type of file. Providers other than these won't be admitted and won't be counted as valid evidence.
  {.is-warning}

### Set the minimum count of evidences

In the select menu, choose the **Set the minimum count of evidences** option.

Next, type in the form the number of numeric *(integer)* evidences that the report should have.

> The minimum count of evidences is **0 evidences** by default.
  {.is-info}