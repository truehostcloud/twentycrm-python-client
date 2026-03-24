# MessageThreadForResponse

Message Thread

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**messages** | [**List[MessageForResponse]**](MessageForResponse.md) | Messages from the thread. | [optional] 
**message_channel_message_associations** | [**List[MessageChannelMessageAssociationForResponse]**](MessageChannelMessageAssociationForResponse.md) | Messages from the channel. | [optional] 

## Example

```python
from twentycrm_client.models.message_thread_for_response import MessageThreadForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MessageThreadForResponse from a JSON string
message_thread_for_response_instance = MessageThreadForResponse.from_json(json)
# print the JSON string representation of the object
print(MessageThreadForResponse.to_json())

# convert the object into a dict
message_thread_for_response_dict = message_thread_for_response_instance.to_dict()
# create an instance of MessageThreadForResponse from a dict
message_thread_for_response_from_dict = MessageThreadForResponse.from_dict(message_thread_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


