# TaskBodyV2

Task body

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**blocknote** | **str** |  | [optional] 
**markdown** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.task_body_v2 import TaskBodyV2

# TODO update the JSON string below
json = "{}"
# create an instance of TaskBodyV2 from a JSON string
task_body_v2_instance = TaskBodyV2.from_json(json)
# print the JSON string representation of the object
print(TaskBodyV2.to_json())

# convert the object into a dict
task_body_v2_dict = task_body_v2_instance.to_dict()
# create an instance of TaskBodyV2 from a dict
task_body_v2_from_dict = TaskBodyV2.from_dict(task_body_v2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


