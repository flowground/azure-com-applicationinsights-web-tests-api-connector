# ![LOGO](logo.png) ApplicationInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationInsightsManagementClient API (version 2015-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/applicationinsights-webTests_API/2015-05-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:19+03:00

## API Description

Azure Application Insights client for web test based alerting.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get all Application Insights web test alerts definitions within a subscription.

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.

### Get all Application Insights web tests defined for the specified component.

#### Input Parameters
* `componentName` - _required_ - The name of the Application Insights component resource.
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.

### Get all Application Insights web tests defined within a specified resource group.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.

### Deletes an Application Insights web test.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceGroupName` - _required_ - The name of the resource group.
* `webTestName` - _required_ - The name of the Application Insights webtest resource.
* `api-version` - _required_ - Client Api Version.

### Get a specific Application Insights web test definition.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `webTestName` - _required_ - The name of the Application Insights webtest resource.

### Creates or updates an Application Insights web test definition.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `webTestName` - _required_ - The name of the Application Insights webtest resource.

### Creates or updates an Application Insights web test definition.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `webTestName` - _required_ - The name of the Application Insights webtest resource.

## License

**flow**ground :- Telekom iPaaS / azure-com-applicationinsights-web-tests-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
