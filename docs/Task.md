# Task

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
from twentycrm_client.models.task import Task

# TODO update the JSON string below
json = "{}"
# create an instance of Task from a JSON string
task_instance = Task.from_json(json)
# print the JSON string representation of the object
print(Task.to_json())

# convert the object into a dict
task_dict = task_instance.to_dict()
# create an instance of Task from a dict
task_from_dict = Task.from_dict(task_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


