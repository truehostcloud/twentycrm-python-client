# MessageParticipant

Message Participants

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**role** | **str** | Role | [optional] 
**handle** | **str** | Handle | [optional] 
**display_name** | **str** | Display Name | [optional] 
**message_id** | **UUID** |  | [optional] 
**person_id** | **UUID** |  | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_participant import MessageParticipant

# TODO update the JSON string below
json = "{}"
# create an instance of MessageParticipant from a JSON string
message_participant_instance = MessageParticipant.from_json(json)
# print the JSON string representation of the object
print(MessageParticipant.to_json())

# convert the object into a dict
message_participant_dict = message_participant_instance.to_dict()
# create an instance of MessageParticipant from a dict
message_participant_from_dict = MessageParticipant.from_dict(message_participant_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


