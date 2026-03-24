# CalendarEventParticipant

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
from twentycrm_client.models.calendar_event_participant import CalendarEventParticipant

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventParticipant from a JSON string
calendar_event_participant_instance = CalendarEventParticipant.from_json(json)
# print the JSON string representation of the object
print(CalendarEventParticipant.to_json())

# convert the object into a dict
calendar_event_participant_dict = calendar_event_participant_instance.to_dict()
# create an instance of CalendarEventParticipant from a dict
calendar_event_participant_from_dict = CalendarEventParticipant.from_dict(calendar_event_participant_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


