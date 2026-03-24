# MergeManyWorkflowVersions200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merge_workflow_versions** | [**WorkflowVersionForResponse**](WorkflowVersionForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.merge_many_workflow_versions200_response_data import MergeManyWorkflowVersions200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of MergeManyWorkflowVersions200ResponseData from a JSON string
merge_many_workflow_versions200_response_data_instance = MergeManyWorkflowVersions200ResponseData.from_json(json)
# print the JSON string representation of the object
print(MergeManyWorkflowVersions200ResponseData.to_json())

# convert the object into a dict
merge_many_workflow_versions200_response_data_dict = merge_many_workflow_versions200_response_data_instance.to_dict()
# create an instance of MergeManyWorkflowVersions200ResponseData from a dict
merge_many_workflow_versions200_response_data_from_dict = MergeManyWorkflowVersions200ResponseData.from_dict(merge_many_workflow_versions200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


