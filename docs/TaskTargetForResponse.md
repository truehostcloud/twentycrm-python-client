# TaskTargetForResponse

A task target

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**target_company** | **str** | TaskTarget target | [optional] 
**target_opportunity** | **str** | TaskTarget target | [optional] 
**target_person** | **str** | TaskTarget target | [optional] 
**task_id** | **UUID** |  | [optional] 
**task** | [**TaskForResponse**](TaskForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.task_target_for_response import TaskTargetForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of TaskTargetForResponse from a JSON string
task_target_for_response_instance = TaskTargetForResponse.from_json(json)
# print the JSON string representation of the object
print(TaskTargetForResponse.to_json())

# convert the object into a dict
task_target_for_response_dict = task_target_for_response_instance.to_dict()
# create an instance of TaskTargetForResponse from a dict
task_target_for_response_from_dict = TaskTargetForResponse.from_dict(task_target_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


