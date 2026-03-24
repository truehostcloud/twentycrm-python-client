# GroupByTaskTargets200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**task_targets_group_by** | [**List[GroupByTaskTargets200ResponseDataTaskTargetsGroupByInner]**](GroupByTaskTargets200ResponseDataTaskTargetsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_task_targets200_response_data import GroupByTaskTargets200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByTaskTargets200ResponseData from a JSON string
group_by_task_targets200_response_data_instance = GroupByTaskTargets200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByTaskTargets200ResponseData.to_json())

# convert the object into a dict
group_by_task_targets200_response_data_dict = group_by_task_targets200_response_data_instance.to_dict()
# create an instance of GroupByTaskTargets200ResponseData from a dict
group_by_task_targets200_response_data_from_dict = GroupByTaskTargets200ResponseData.from_dict(group_by_task_targets200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


