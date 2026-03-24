# TaskTargetForUpdate

A task target

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_company** | **str** | TaskTarget target | [optional] 
**target_opportunity** | **str** | TaskTarget target | [optional] 
**target_person** | **str** | TaskTarget target | [optional] 
**task_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.task_target_for_update import TaskTargetForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of TaskTargetForUpdate from a JSON string
task_target_for_update_instance = TaskTargetForUpdate.from_json(json)
# print the JSON string representation of the object
print(TaskTargetForUpdate.to_json())

# convert the object into a dict
task_target_for_update_dict = task_target_for_update_instance.to_dict()
# create an instance of TaskTargetForUpdate from a dict
task_target_for_update_from_dict = TaskTargetForUpdate.from_dict(task_target_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


