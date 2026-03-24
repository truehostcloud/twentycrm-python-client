# FindOneWorkflowVersion200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**workflow_version** | [**WorkflowVersionForResponse**](WorkflowVersionForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_one_workflow_version200_response_data import FindOneWorkflowVersion200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindOneWorkflowVersion200ResponseData from a JSON string
find_one_workflow_version200_response_data_instance = FindOneWorkflowVersion200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindOneWorkflowVersion200ResponseData.to_json())

# convert the object into a dict
find_one_workflow_version200_response_data_dict = find_one_workflow_version200_response_data_instance.to_dict()
# create an instance of FindOneWorkflowVersion200ResponseData from a dict
find_one_workflow_version200_response_data_from_dict = FindOneWorkflowVersion200ResponseData.from_dict(find_one_workflow_version200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


