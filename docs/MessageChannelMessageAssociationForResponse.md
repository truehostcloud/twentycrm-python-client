# MessageChannelMessageAssociationForResponse

Message Synced with a Message Channel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**message_external_id** | **str** | Message id from the messaging provider | [optional] 
**message_thread_external_id** | **str** | Thread id from the messaging provider | [optional] 
**direction** | **str** | Message Direction | [optional] 
**message_id** | **UUID** |  | [optional] 
**message_channel_id** | **UUID** |  | [optional] 
**message_thread_id** | **UUID** |  | [optional] 
**message** | [**MessageForResponse**](MessageForResponse.md) |  | [optional] 
**message_channel** | [**MessageChannelForResponse**](MessageChannelForResponse.md) |  | [optional] 
**message_thread** | [**MessageThreadForResponse**](MessageThreadForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.message_channel_message_association_for_response import MessageChannelMessageAssociationForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MessageChannelMessageAssociationForResponse from a JSON string
message_channel_message_association_for_response_instance = MessageChannelMessageAssociationForResponse.from_json(json)
# print the JSON string representation of the object
print(MessageChannelMessageAssociationForResponse.to_json())

# convert the object into a dict
message_channel_message_association_for_response_dict = message_channel_message_association_for_response_instance.to_dict()
# create an instance of MessageChannelMessageAssociationForResponse from a dict
message_channel_message_association_for_response_from_dict = MessageChannelMessageAssociationForResponse.from_dict(message_channel_message_association_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


