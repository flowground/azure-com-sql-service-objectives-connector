# ![LOGO](logo.png) Azure SQL Database **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-serviceObjectives/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:12+03:00

## API Description

Provides create, read, update and delete functionality for Azure SQL Database resources including servers, databases, elastic pools, recommendations, operations, and usage metrics.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns database service objectives.

*Tags:* `ServiceObjectives`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Gets a database service objective.

*Tags:* `ServiceObjectives`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `serviceObjectiveName` - _required_ - The name of the service objective to retrieve.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-service-objectives-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
