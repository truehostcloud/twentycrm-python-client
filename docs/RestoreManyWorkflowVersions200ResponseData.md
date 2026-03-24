# RestoreManyWorkflowVersions200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**restore_workflow_versions** | [**List[WorkflowVersionForResponse]**](WorkflowVersionForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_many_workflow_versions200_response_data import RestoreManyWorkflowVersions200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreManyWorkflowVersions200ResponseData from a JSON string
restore_many_workflow_versions200_response_data_instance = RestoreManyWorkflowVersions200ResponseData.from_json(json)
# print the JSON string representation of the object
print(RestoreManyWorkflowVersions200ResponseData.to_json())

# convert the object into a dict
restore_many_workflow_versions200_response_data_dict = restore_many_workflow_versions200_response_data_instance.to_dict()
# create an instance of RestoreManyWorkflowVersions200ResponseData from a dict
restore_many_workflow_versions200_response_data_from_dict = RestoreManyWorkflowVersions200ResponseData.from_dict(restore_many_workflow_versions200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


