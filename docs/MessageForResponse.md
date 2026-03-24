# MessageForResponse

Message

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**id** | **UUID** | Id | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**header_message_id** | **str** | Message id from the message header | [optional] 
**direction** | **str** | Message Direction | [optional] 
**subject** | **str** | Subject | [optional] 
**text** | **str** | Text | [optional] 
**received_at** | **datetime** | The date the message was received | [optional] 
**message_thread_id** | **UUID** |  | [optional] 
**message_thread** | [**MessageThreadForResponse**](MessageThreadForResponse.md) |  | [optional] 
**message_participants** | [**List[MessageParticipantForResponse]**](MessageParticipantForResponse.md) | Message Participants | [optional] 
**message_channel_message_associations** | [**List[MessageChannelMessageAssociationForResponse]**](MessageChannelMessageAssociationForResponse.md) | Messages from the channel. | [optional] 

## Example

```python
from twentycrm_client.models.message_for_response import MessageForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MessageForResponse from a JSON string
message_for_response_instance = MessageForResponse.from_json(json)
# print the JSON string representation of the object
print(MessageForResponse.to_json())

# convert the object into a dict
message_for_response_dict = message_for_response_instance.to_dict()
# create an instance of MessageForResponse from a dict
message_for_response_from_dict = MessageForResponse.from_dict(message_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


