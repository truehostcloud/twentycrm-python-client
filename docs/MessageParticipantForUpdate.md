# MessageParticipantForUpdate

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
from twentycrm_client.models.message_participant_for_update import MessageParticipantForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of MessageParticipantForUpdate from a JSON string
message_participant_for_update_instance = MessageParticipantForUpdate.from_json(json)
# print the JSON string representation of the object
print(MessageParticipantForUpdate.to_json())

# convert the object into a dict
message_participant_for_update_dict = message_participant_for_update_instance.to_dict()
# create an instance of MessageParticipantForUpdate from a dict
message_participant_for_update_from_dict = MessageParticipantForUpdate.from_dict(message_participant_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


