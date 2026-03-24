# FindWorkflowRunDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[WorkflowRun]**](WorkflowRun.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_workflow_run_duplicates_request import FindWorkflowRunDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindWorkflowRunDuplicatesRequest from a JSON string
find_workflow_run_duplicates_request_instance = FindWorkflowRunDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindWorkflowRunDuplicatesRequest.to_json())

# convert the object into a dict
find_workflow_run_duplicates_request_dict = find_workflow_run_duplicates_request_instance.to_dict()
# create an instance of FindWorkflowRunDuplicatesRequest from a dict
find_workflow_run_duplicates_request_from_dict = FindWorkflowRunDuplicatesRequest.from_dict(find_workflow_run_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


