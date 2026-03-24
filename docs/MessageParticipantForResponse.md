# MessageParticipantForResponse

Message Participants

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**role** | **str** | Role | [optional] 
**handle** | **str** | Handle | [optional] 
**display_name** | **str** | Display Name | [optional] 
**message_id** | **UUID** |  | [optional] 
**person_id** | **UUID** |  | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 
**message** | [**MessageForResponse**](MessageForResponse.md) |  | [optional] 
**person** | [**PersonForResponse**](PersonForResponse.md) |  | [optional] 
**workspace_member** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.message_participant_for_response import MessageParticipantForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MessageParticipantForResponse from a JSON string
message_participant_for_response_instance = MessageParticipantForResponse.from_json(json)
# print the JSON string representation of the object
print(MessageParticipantForResponse.to_json())

# convert the object into a dict
message_participant_for_response_dict = message_participant_for_response_instance.to_dict()
# create an instance of MessageParticipantForResponse from a dict
message_participant_for_response_from_dict = MessageParticipantForResponse.from_dict(message_participant_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


