## Processors: WorkItemDelete

>**_This documentation is for a preview version of the Azure DevOps Migration Tools._ If you are not using the preview version then please head over to the main [documentation](https://nkdagility.github.io/azure-devops-migration-tools).**

[Overview](../././index.md) > [Reference](.././index.md) > [API v1](../index.md) > [Processors](./index.md)> **WorkItemDelete**

missng XML code comments

### Options

| Parameter name         | Type    | Description                              | Default Value                            |
|------------------------|---------|------------------------------------------|------------------------------------------|
| Enabled | Boolean | missng XML code comments | missng XML code comments |
| WIQLQueryBit | String | missng XML code comments | missng XML code comments |
| WIQLOrderBit | String | missng XML code comments | missng XML code comments |
| WorkItemIDs | IList | missng XML code comments | missng XML code comments |
| FilterWorkItemsThatAlreadyExistInTarget | Boolean | missng XML code comments | missng XML code comments |
| PauseAfterEachWorkItem | Boolean | missng XML code comments | missng XML code comments |
| WorkItemCreateRetryLimit | Int32 | missng XML code comments | missng XML code comments |


### Example JSON

```JSON
{
  "$type": "WorkItemDeleteConfig",
  "Enabled": false,
  "WIQLQueryBit": "AND  [Microsoft.VSTS.Common.ClosedDate] = '' AND [System.WorkItemType] NOT IN ('Test Suite', 'Test Plan')",
  "WIQLOrderBit": "[System.ChangedDate] desc",
  "WorkItemIDs": null,
  "FilterWorkItemsThatAlreadyExistInTarget": false,
  "PauseAfterEachWorkItem": false,
  "WorkItemCreateRetryLimit": 0
}
```