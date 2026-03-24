# TaskForUpdate

A task

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**position** | **float** | Task record position | [optional] 
**title** | **str** | Task title | [optional] 
**body_v2** | [**TaskBodyV2**](TaskBodyV2.md) |  | [optional] 
**due_at** | **datetime** | Task due date | [optional] 
**status** | **str** | Task status | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 
**assignee_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.task_for_update import TaskForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of TaskForUpdate from a JSON string
task_for_update_instance = TaskForUpdate.from_json(json)
# print the JSON string representation of the object
print(TaskForUpdate.to_json())

# convert the object into a dict
task_for_update_dict = task_for_update_instance.to_dict()
# create an instance of TaskForUpdate from a dict
task_for_update_from_dict = TaskForUpdate.from_dict(task_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


