# FindWorkflowDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Workflow]**](Workflow.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_workflow_duplicates_request import FindWorkflowDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindWorkflowDuplicatesRequest from a JSON string
find_workflow_duplicates_request_instance = FindWorkflowDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindWorkflowDuplicatesRequest.to_json())

# convert the object into a dict
find_workflow_duplicates_request_dict = find_workflow_duplicates_request_instance.to_dict()
# create an instance of FindWorkflowDuplicatesRequest from a dict
find_workflow_duplicates_request_from_dict = FindWorkflowDuplicatesRequest.from_dict(find_workflow_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


