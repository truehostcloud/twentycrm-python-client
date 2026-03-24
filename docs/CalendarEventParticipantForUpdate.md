# CalendarEventParticipantForUpdate

Calendar event participants

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**handle** | **str** | Handle | [optional] 
**display_name** | **str** | Display Name | [optional] 
**is_organizer** | **bool** | Is Organizer | [optional] 
**response_status** | **str** | Response Status | [optional] 
**calendar_event_id** | **UUID** |  | [optional] 
**person_id** | **UUID** |  | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_participant_for_update import CalendarEventParticipantForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventParticipantForUpdate from a JSON string
calendar_event_participant_for_update_instance = CalendarEventParticipantForUpdate.from_json(json)
# print the JSON string representation of the object
print(CalendarEventParticipantForUpdate.to_json())

# convert the object into a dict
calendar_event_participant_for_update_dict = calendar_event_participant_for_update_instance.to_dict()
# create an instance of CalendarEventParticipantForUpdate from a dict
calendar_event_participant_for_update_from_dict = CalendarEventParticipantForUpdate.from_dict(calendar_event_participant_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


