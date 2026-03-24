# WorkflowVersionForUpdate

A workflow version

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The workflow version name | [optional] 
**trigger** | **object** | Json object to provide trigger | [optional] 
**steps** | **object** | Json object to provide steps | [optional] 
**status** | **str** | The workflow version status | [optional] 
**position** | **float** | Workflow version position | [optional] 
**workflow_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_version_for_update import WorkflowVersionForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowVersionForUpdate from a JSON string
workflow_version_for_update_instance = WorkflowVersionForUpdate.from_json(json)
# print the JSON string representation of the object
print(WorkflowVersionForUpdate.to_json())

# convert the object into a dict
workflow_version_for_update_dict = workflow_version_for_update_instance.to_dict()
# create an instance of WorkflowVersionForUpdate from a dict
workflow_version_for_update_from_dict = WorkflowVersionForUpdate.from_dict(workflow_version_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


