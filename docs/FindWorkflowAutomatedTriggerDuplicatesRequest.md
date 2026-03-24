# FindWorkflowAutomatedTriggerDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[WorkflowAutomatedTrigger]**](WorkflowAutomatedTrigger.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_workflow_automated_trigger_duplicates_request import FindWorkflowAutomatedTriggerDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindWorkflowAutomatedTriggerDuplicatesRequest from a JSON string
find_workflow_automated_trigger_duplicates_request_instance = FindWorkflowAutomatedTriggerDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindWorkflowAutomatedTriggerDuplicatesRequest.to_json())

# convert the object into a dict
find_workflow_automated_trigger_duplicates_request_dict = find_workflow_automated_trigger_duplicates_request_instance.to_dict()
# create an instance of FindWorkflowAutomatedTriggerDuplicatesRequest from a dict
find_workflow_automated_trigger_duplicates_request_from_dict = FindWorkflowAutomatedTriggerDuplicatesRequest.from_dict(find_workflow_automated_trigger_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


