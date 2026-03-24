# WorkflowAutomatedTriggerForResponse

A workflow automated trigger

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**type** | **str** | The workflow automated trigger type | [optional] 
**settings** | **object** | The workflow automated trigger settings | [optional] 
**workflow_id** | **UUID** |  | [optional] 
**workflow** | [**WorkflowForResponse**](WorkflowForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_automated_trigger_for_response import WorkflowAutomatedTriggerForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowAutomatedTriggerForResponse from a JSON string
workflow_automated_trigger_for_response_instance = WorkflowAutomatedTriggerForResponse.from_json(json)
# print the JSON string representation of the object
print(WorkflowAutomatedTriggerForResponse.to_json())

# convert the object into a dict
workflow_automated_trigger_for_response_dict = workflow_automated_trigger_for_response_instance.to_dict()
# create an instance of WorkflowAutomatedTriggerForResponse from a dict
workflow_automated_trigger_for_response_from_dict = WorkflowAutomatedTriggerForResponse.from_dict(workflow_automated_trigger_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


