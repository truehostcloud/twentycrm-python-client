# WorkflowAutomatedTrigger

A workflow automated trigger

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The workflow automated trigger type | 
**settings** | **object** | The workflow automated trigger settings | 
**workflow_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_automated_trigger import WorkflowAutomatedTrigger

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowAutomatedTrigger from a JSON string
workflow_automated_trigger_instance = WorkflowAutomatedTrigger.from_json(json)
# print the JSON string representation of the object
print(WorkflowAutomatedTrigger.to_json())

# convert the object into a dict
workflow_automated_trigger_dict = workflow_automated_trigger_instance.to_dict()
# create an instance of WorkflowAutomatedTrigger from a dict
workflow_automated_trigger_from_dict = WorkflowAutomatedTrigger.from_dict(workflow_automated_trigger_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


