# WorkflowAutomatedTriggerForUpdate

A workflow automated trigger

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The workflow automated trigger type | [optional] 
**settings** | **object** | The workflow automated trigger settings | [optional] 
**workflow_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_automated_trigger_for_update import WorkflowAutomatedTriggerForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowAutomatedTriggerForUpdate from a JSON string
workflow_automated_trigger_for_update_instance = WorkflowAutomatedTriggerForUpdate.from_json(json)
# print the JSON string representation of the object
print(WorkflowAutomatedTriggerForUpdate.to_json())

# convert the object into a dict
workflow_automated_trigger_for_update_dict = workflow_automated_trigger_for_update_instance.to_dict()
# create an instance of WorkflowAutomatedTriggerForUpdate from a dict
workflow_automated_trigger_for_update_from_dict = WorkflowAutomatedTriggerForUpdate.from_dict(workflow_automated_trigger_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


