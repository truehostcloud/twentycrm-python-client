# GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[MessageThreadForResponse]**](MessageThreadForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_message_threads200_response_data_message_threads_group_by_inner import GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner from a JSON string
group_by_message_threads200_response_data_message_threads_group_by_inner_instance = GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner.to_json())

# convert the object into a dict
group_by_message_threads200_response_data_message_threads_group_by_inner_dict = group_by_message_threads200_response_data_message_threads_group_by_inner_instance.to_dict()
# create an instance of GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner from a dict
group_by_message_threads200_response_data_message_threads_group_by_inner_from_dict = GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner.from_dict(group_by_message_threads200_response_data_message_threads_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


