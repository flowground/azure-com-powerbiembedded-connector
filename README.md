# ![LOGO](logo.png) Power BI Embedded Management Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Power BI Embedded Management Client API (version 2016-01-29).

Generated from: https://api.apis.guru/v2/specs/azure.com/powerbiembedded/2016-01-29/swagger.json<br/>
Generated at: 2019-05-07T17:38:37+03:00

## API Description

Client to manage your Power BI Embedded workspace collections and retrieve workspaces.

## Authorization

This API does not require authorization.

## Actions

### Indicates which operations can be performed by the Power BI Resource Provider.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Verify the specified Power BI Workspace Collection name is valid and not already in use.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Azure location
* `api-version` - _required_ - Client Api Version.

### Retrieves all existing Power BI workspace collections in the specified subscription.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Migrates an existing Power BI Workspace Collection to a different resource group and/or subscription.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `api-version` - _required_ - Client Api Version.

### Retrieves all existing Power BI workspace collections in the specified resource group.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `api-version` - _required_ - Client Api Version.

### Delete a Power BI Workspace Collection.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `workspaceCollectionName` - _required_ - Power BI Embedded Workspace Collection name
* `api-version` - _required_ - Client Api Version.

### Retrieves an existing Power BI Workspace Collection.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `workspaceCollectionName` - _required_ - Power BI Embedded Workspace Collection name
* `api-version` - _required_ - Client Api Version.

### Update an existing Power BI Workspace Collection with the specified properties.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `workspaceCollectionName` - _required_ - Power BI Embedded Workspace Collection name
* `api-version` - _required_ - Client Api Version.

### Creates a new Power BI Workspace Collection with the specified properties. A Power BI Workspace Collection contains one or more workspaces, and can be used to provision keys that provide API access to those workspaces.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `workspaceCollectionName` - _required_ - Power BI Embedded Workspace Collection name
* `api-version` - _required_ - Client Api Version.

### Retrieves the primary and secondary access keys for the specified Power BI Workspace Collection.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `workspaceCollectionName` - _required_ - Power BI Embedded Workspace Collection name
* `api-version` - _required_ - Client Api Version.

### Regenerates the primary or secondary access key for the specified Power BI Workspace Collection.

*Tags:* `WorkspaceCollections`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `workspaceCollectionName` - _required_ - Power BI Embedded Workspace Collection name
* `api-version` - _required_ - Client Api Version.

### Retrieves all existing Power BI workspaces in the specified workspace collection.

*Tags:* `Workspaces`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Azure resource group
* `workspaceCollectionName` - _required_ - Power BI Embedded Workspace Collection name
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-powerbiembedded-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
