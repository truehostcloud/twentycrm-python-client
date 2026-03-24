# MessageForUpdate

Message

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**header_message_id** | **str** | Message id from the message header | [optional] 
**direction** | **str** | Message Direction | [optional] 
**subject** | **str** | Subject | [optional] 
**text** | **str** | Text | [optional] 
**received_at** | **datetime** | The date the message was received | [optional] 
**message_thread_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_for_update import MessageForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of MessageForUpdate from a JSON string
message_for_update_instance = MessageForUpdate.from_json(json)
# print the JSON string representation of the object
print(MessageForUpdate.to_json())

# convert the object into a dict
message_for_update_dict = message_for_update_instance.to_dict()
# create an instance of MessageForUpdate from a dict
message_for_update_from_dict = MessageForUpdate.from_dict(message_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


