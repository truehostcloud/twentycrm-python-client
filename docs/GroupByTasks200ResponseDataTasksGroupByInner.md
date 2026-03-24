# GroupByTasks200ResponseDataTasksGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[TaskForResponse]**](TaskForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_tasks200_response_data_tasks_group_by_inner import GroupByTasks200ResponseDataTasksGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByTasks200ResponseDataTasksGroupByInner from a JSON string
group_by_tasks200_response_data_tasks_group_by_inner_instance = GroupByTasks200ResponseDataTasksGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByTasks200ResponseDataTasksGroupByInner.to_json())

# convert the object into a dict
group_by_tasks200_response_data_tasks_group_by_inner_dict = group_by_tasks200_response_data_tasks_group_by_inner_instance.to_dict()
# create an instance of GroupByTasks200ResponseDataTasksGroupByInner from a dict
group_by_tasks200_response_data_tasks_group_by_inner_from_dict = GroupByTasks200ResponseDataTasksGroupByInner.from_dict(group_by_tasks200_response_data_tasks_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


