# MessageChannelMessageAssociation

Message Synced with a Message Channel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_external_id** | **str** | Message id from the messaging provider | [optional] 
**message_thread_external_id** | **str** | Thread id from the messaging provider | [optional] 
**direction** | **str** | Message Direction | [optional] 
**message_id** | **UUID** |  | [optional] 
**message_channel_id** | **UUID** |  | [optional] 
**message_thread_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_channel_message_association import MessageChannelMessageAssociation

# TODO update the JSON string below
json = "{}"
# create an instance of MessageChannelMessageAssociation from a JSON string
message_channel_message_association_instance = MessageChannelMessageAssociation.from_json(json)
# print the JSON string representation of the object
print(MessageChannelMessageAssociation.to_json())

# convert the object into a dict
message_channel_message_association_dict = message_channel_message_association_instance.to_dict()
# create an instance of MessageChannelMessageAssociation from a dict
message_channel_message_association_from_dict = MessageChannelMessageAssociation.from_dict(message_channel_message_association_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


