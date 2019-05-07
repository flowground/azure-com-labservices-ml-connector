# ![LOGO](logo.png) ManagedLabsClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ManagedLabsClient API (version 2018-10-15).

Generated from: https://api.apis.guru/v2/specs/azure.com/labservices-ML/2018-10-15/swagger.json<br/>
Generated at: 2019-05-07T17:38:17+03:00

## API Description

The Managed Labs Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Result of the request to list REST API operations

*Tags:* `ProviderOperations`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Gets the virtual machine details

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($expand=environment)'
* `api-version` - _required_ - Client API version.

### Get batch operation status

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Gets the status of long running operation

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Get personal preferences for a user

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### List Environments for the user

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### List labs for the user.

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Register a user to a managed lab

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Resets the user password on an environment This operation can take a while to complete

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Starts an environment by starting all resources inside the environment. This operation can take a while to complete

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Stops an environment by stopping all resources inside the environment This operation can take a while to complete

*Tags:* `GlobalUsers`

#### Input Parameters
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### List lab accounts in a subscription.

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($expand=sizeConfiguration)'
* `$filter` - _optional_ - The filter to apply to the operation.
* `$top` - _optional_ - The maximum number of resources to return from the operation.
* `$orderby` - _optional_ - The ordering expression for the results, using OData notation.
* `api-version` - _required_ - Client API version.

### Get operation

*Tags:* `Operations`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `locationName` - _required_ - The name of the location.
* `operationName` - _required_ - The name of the operation.
* `api-version` - _required_ - Client API version.

### List lab accounts in a resource group.

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($expand=sizeConfiguration)'
* `$filter` - _optional_ - The filter to apply to the operation.
* `$top` - _optional_ - The maximum number of resources to return from the operation.
* `$orderby` - _optional_ - The ordering expression for the results, using OData notation.
* `api-version` - _required_ - Client API version.

### Delete lab account. This operation can take a while to complete

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `api-version` - _required_ - Client API version.

### Get lab account

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($expand=sizeConfiguration)'
* `api-version` - _required_ - Client API version.

### Modify properties of lab accounts.

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `api-version` - _required_ - Client API version.

### Create or replace an existing Lab Account.

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `api-version` - _required_ - Client API version.

### Create a lab in a lab account.

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `api-version` - _required_ - Client API version.

### List gallery images in a given lab account.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=author)'
* `$filter` - _optional_ - The filter to apply to the operation.
* `$top` - _optional_ - The maximum number of resources to return from the operation.
* `$orderby` - _optional_ - The ordering expression for the results, using OData notation.
* `api-version` - _required_ - Client API version.

### Delete gallery image.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `galleryImageName` - _required_ - The name of the gallery Image.
* `api-version` - _required_ - Client API version.

### Get gallery image

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `galleryImageName` - _required_ - The name of the gallery Image.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=author)'
* `api-version` - _required_ - Client API version.

### Modify properties of gallery images.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `galleryImageName` - _required_ - The name of the gallery Image.
* `api-version` - _required_ - Client API version.

### Create or replace an existing Gallery Image.

*Tags:* `GalleryImages`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `galleryImageName` - _required_ - The name of the gallery Image.
* `api-version` - _required_ - Client API version.

### Get regional availability information for each size category configured under a lab account

*Tags:* `LabAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `api-version` - _required_ - Client API version.

### List labs in a given lab account.

*Tags:* `Labs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=maxUsersInLab)'
* `$filter` - _optional_ - The filter to apply to the operation.
* `$top` - _optional_ - The maximum number of resources to return from the operation.
* `$orderby` - _optional_ - The ordering expression for the results, using OData notation.
* `api-version` - _required_ - Client API version.

### Delete lab. This operation can take a while to complete

*Tags:* `Labs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `api-version` - _required_ - Client API version.

### Get lab

*Tags:* `Labs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=maxUsersInLab)'
* `api-version` - _required_ - Client API version.

### Modify properties of labs.

*Tags:* `Labs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `api-version` - _required_ - Client API version.

### Create or replace an existing Lab.

*Tags:* `Labs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `api-version` - _required_ - Client API version.

### Add users to a lab

*Tags:* `Labs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `api-version` - _required_ - Client API version.

### List environment setting in a given lab.

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=publishingState)'
* `$filter` - _optional_ - The filter to apply to the operation.
* `$top` - _optional_ - The maximum number of resources to return from the operation.
* `$orderby` - _optional_ - The ordering expression for the results, using OData notation.
* `api-version` - _required_ - Client API version.

### Delete environment setting. This operation can take a while to complete

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `api-version` - _required_ - Client API version.

### Get environment setting

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=publishingState)'
* `api-version` - _required_ - Client API version.

### Modify properties of environment setting.

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `api-version` - _required_ - Client API version.

### Create or replace an existing Environment Setting. This operation can take a while to complete

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `api-version` - _required_ - Client API version.

### Claims a random environment for a user in an environment settings

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `api-version` - _required_ - Client API version.

### List environments in a given environment setting.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($expand=networkInterface)'
* `$filter` - _optional_ - The filter to apply to the operation.
* `$top` - _optional_ - The maximum number of resources to return from the operation.
* `$orderby` - _optional_ - The ordering expression for the results, using OData notation.
* `api-version` - _required_ - Client API version.

### Delete environment. This operation can take a while to complete

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `api-version` - _required_ - Client API version.

### Get environment

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($expand=networkInterface)'
* `api-version` - _required_ - Client API version.

### Modify properties of environments.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `api-version` - _required_ - Client API version.

### Create or replace an existing Environment.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `api-version` - _required_ - Client API version.

### Claims the environment and assigns it to the user

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `api-version` - _required_ - Client API version.

### Resets the user password on an environment This operation can take a while to complete

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `api-version` - _required_ - Client API version.

### Starts an environment by starting all resources inside the environment. This operation can take a while to complete

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `api-version` - _required_ - Client API version.

### Stops an environment by stopping all resources inside the environment This operation can take a while to complete

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `environmentName` - _required_ - The name of the environment.
* `api-version` - _required_ - Client API version.

### Provisions/deprovisions required resources for an environment setting based on current state of the lab/environment setting.

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `api-version` - _required_ - Client API version.

### Starts a template by starting all resources inside the template. This operation can take a while to complete

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `api-version` - _required_ - Client API version.

### Starts a template by starting all resources inside the template. This operation can take a while to complete

*Tags:* `EnvironmentSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `environmentSettingName` - _required_ - The name of the environment Setting.
* `api-version` - _required_ - Client API version.

### Register to managed lab.

*Tags:* `Labs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `api-version` - _required_ - Client API version.

### List users in a given lab.

*Tags:* `Users`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=email)'
* `$filter` - _optional_ - The filter to apply to the operation.
* `$top` - _optional_ - The maximum number of resources to return from the operation.
* `$orderby` - _optional_ - The ordering expression for the results, using OData notation.
* `api-version` - _required_ - Client API version.

### Delete user. This operation can take a while to complete

*Tags:* `Users`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Get user

*Tags:* `Users`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `userName` - _required_ - The name of the user.
* `$expand` - _optional_ - Specify the $expand query. Example: 'properties($select=email)'
* `api-version` - _required_ - Client API version.

### Modify properties of users.

*Tags:* `Users`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

### Create or replace an existing User.

*Tags:* `Users`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `labAccountName` - _required_ - The name of the lab Account.
* `labName` - _required_ - The name of the lab.
* `userName` - _required_ - The name of the user.
* `api-version` - _required_ - Client API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-labservices-ml-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
