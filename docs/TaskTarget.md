# TaskTarget

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
from twentycrm_client.models.task_target import TaskTarget

# TODO update the JSON string below
json = "{}"
# create an instance of TaskTarget from a JSON string
task_target_instance = TaskTarget.from_json(json)
# print the JSON string representation of the object
print(TaskTarget.to_json())

# convert the object into a dict
task_target_dict = task_target_instance.to_dict()
# create an instance of TaskTarget from a dict
task_target_from_dict = TaskTarget.from_dict(task_target_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


