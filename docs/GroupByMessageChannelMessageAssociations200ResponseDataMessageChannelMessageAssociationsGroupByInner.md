# GroupByMessageChannelMessageAssociations200ResponseDataMessageChannelMessageAssociationsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[MessageChannelMessageAssociationForResponse]**](MessageChannelMessageAssociationForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_message_channel_message_associations200_response_data_message_channel_message_associations_group_by_inner import GroupByMessageChannelMessageAssociations200ResponseDataMessageChannelMessageAssociationsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByMessageChannelMessageAssociations200ResponseDataMessageChannelMessageAssociationsGroupByInner from a JSON string
group_by_message_channel_message_associations200_response_data_message_channel_message_associations_group_by_inner_instance = GroupByMessageChannelMessageAssociations200ResponseDataMessageChannelMessageAssociationsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByMessageChannelMessageAssociations200ResponseDataMessageChannelMessageAssociationsGroupByInner.to_json())

# convert the object into a dict
group_by_message_channel_message_associations200_response_data_message_channel_message_associations_group_by_inner_dict = group_by_message_channel_message_associations200_response_data_message_channel_message_associations_group_by_inner_instance.to_dict()
# create an instance of GroupByMessageChannelMessageAssociations200ResponseDataMessageChannelMessageAssociationsGroupByInner from a dict
group_by_message_channel_message_associations200_response_data_message_channel_message_associations_group_by_inner_from_dict = GroupByMessageChannelMessageAssociations200ResponseDataMessageChannelMessageAssociationsGroupByInner.from_dict(group_by_message_channel_message_associations200_response_data_message_channel_message_associations_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


