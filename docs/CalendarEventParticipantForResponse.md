# CalendarEventParticipantForResponse

Calendar event participants

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**handle** | **str** | Handle | [optional] 
**display_name** | **str** | Display Name | [optional] 
**is_organizer** | **bool** | Is Organizer | [optional] 
**response_status** | **str** | Response Status | [optional] 
**calendar_event_id** | **UUID** |  | [optional] 
**person_id** | **UUID** |  | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 
**calendar_event** | [**CalendarEventForResponse**](CalendarEventForResponse.md) |  | [optional] 
**person** | [**PersonForResponse**](PersonForResponse.md) |  | [optional] 
**workspace_member** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_participant_for_response import CalendarEventParticipantForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventParticipantForResponse from a JSON string
calendar_event_participant_for_response_instance = CalendarEventParticipantForResponse.from_json(json)
# print the JSON string representation of the object
print(CalendarEventParticipantForResponse.to_json())

# convert the object into a dict
calendar_event_participant_for_response_dict = calendar_event_participant_for_response_instance.to_dict()
# create an instance of CalendarEventParticipantForResponse from a dict
calendar_event_participant_for_response_from_dict = CalendarEventParticipantForResponse.from_dict(calendar_event_participant_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


