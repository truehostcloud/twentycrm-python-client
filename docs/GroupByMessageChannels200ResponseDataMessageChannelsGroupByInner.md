# GroupByMessageChannels200ResponseDataMessageChannelsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[MessageChannelForResponse]**](MessageChannelForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_message_channels200_response_data_message_channels_group_by_inner import GroupByMessageChannels200ResponseDataMessageChannelsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByMessageChannels200ResponseDataMessageChannelsGroupByInner from a JSON string
group_by_message_channels200_response_data_message_channels_group_by_inner_instance = GroupByMessageChannels200ResponseDataMessageChannelsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByMessageChannels200ResponseDataMessageChannelsGroupByInner.to_json())

# convert the object into a dict
group_by_message_channels200_response_data_message_channels_group_by_inner_dict = group_by_message_channels200_response_data_message_channels_group_by_inner_instance.to_dict()
# create an instance of GroupByMessageChannels200ResponseDataMessageChannelsGroupByInner from a dict
group_by_message_channels200_response_data_message_channels_group_by_inner_from_dict = GroupByMessageChannels200ResponseDataMessageChannelsGroupByInner.from_dict(group_by_message_channels200_response_data_message_channels_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


