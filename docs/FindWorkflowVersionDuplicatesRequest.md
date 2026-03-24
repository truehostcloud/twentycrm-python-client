# FindWorkflowVersionDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[WorkflowVersion]**](WorkflowVersion.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_workflow_version_duplicates_request import FindWorkflowVersionDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindWorkflowVersionDuplicatesRequest from a JSON string
find_workflow_version_duplicates_request_instance = FindWorkflowVersionDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindWorkflowVersionDuplicatesRequest.to_json())

# convert the object into a dict
find_workflow_version_duplicates_request_dict = find_workflow_version_duplicates_request_instance.to_dict()
# create an instance of FindWorkflowVersionDuplicatesRequest from a dict
find_workflow_version_duplicates_request_from_dict = FindWorkflowVersionDuplicatesRequest.from_dict(find_workflow_version_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


