# TaskForResponse

A task

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**position** | **float** | Task record position | [optional] 
**title** | **str** | Task title | [optional] 
**body_v2** | [**TaskBodyV2**](TaskBodyV2.md) |  | [optional] 
**due_at** | **datetime** | Task due date | [optional] 
**status** | **str** | Task status | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**assignee_id** | **UUID** |  | [optional] 
**attachments** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Task attachments | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the task | [optional] 
**task_targets** | [**List[TaskTargetForResponse]**](TaskTargetForResponse.md) | Task targets | [optional] 
**assignee** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline Activities linked to the task. | [optional] 

## Example

```python
from twentycrm_client.models.task_for_response import TaskForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of TaskForResponse from a JSON string
task_for_response_instance = TaskForResponse.from_json(json)
# print the JSON string representation of the object
print(TaskForResponse.to_json())

# convert the object into a dict
task_for_response_dict = task_for_response_instance.to_dict()
# create an instance of TaskForResponse from a dict
task_for_response_from_dict = TaskForResponse.from_dict(task_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


