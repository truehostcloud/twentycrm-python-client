# GroupByTasks200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tasks_group_by** | [**List[GroupByTasks200ResponseDataTasksGroupByInner]**](GroupByTasks200ResponseDataTasksGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_tasks200_response_data import GroupByTasks200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByTasks200ResponseData from a JSON string
group_by_tasks200_response_data_instance = GroupByTasks200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByTasks200ResponseData.to_json())

# convert the object into a dict
group_by_tasks200_response_data_dict = group_by_tasks200_response_data_instance.to_dict()
# create an instance of GroupByTasks200ResponseData from a dict
group_by_tasks200_response_data_from_dict = GroupByTasks200ResponseData.from_dict(group_by_tasks200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


