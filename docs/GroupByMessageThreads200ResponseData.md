# GroupByMessageThreads200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_threads_group_by** | [**List[GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner]**](GroupByMessageThreads200ResponseDataMessageThreadsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_message_threads200_response_data import GroupByMessageThreads200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByMessageThreads200ResponseData from a JSON string
group_by_message_threads200_response_data_instance = GroupByMessageThreads200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByMessageThreads200ResponseData.to_json())

# convert the object into a dict
group_by_message_threads200_response_data_dict = group_by_message_threads200_response_data_instance.to_dict()
# create an instance of GroupByMessageThreads200ResponseData from a dict
group_by_message_threads200_response_data_from_dict = GroupByMessageThreads200ResponseData.from_dict(group_by_message_threads200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


