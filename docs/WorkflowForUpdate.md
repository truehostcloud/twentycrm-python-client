# WorkflowForUpdate

A workflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The workflow name | [optional] 
**last_published_version_id** | **str** | The workflow last published version id | [optional] 
**statuses** | **List[str]** | The current statuses of the workflow versions | [optional] 
**position** | **float** | Workflow record position | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_for_update import WorkflowForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowForUpdate from a JSON string
workflow_for_update_instance = WorkflowForUpdate.from_json(json)
# print the JSON string representation of the object
print(WorkflowForUpdate.to_json())

# convert the object into a dict
workflow_for_update_dict = workflow_for_update_instance.to_dict()
# create an instance of WorkflowForUpdate from a dict
workflow_for_update_from_dict = WorkflowForUpdate.from_dict(workflow_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


