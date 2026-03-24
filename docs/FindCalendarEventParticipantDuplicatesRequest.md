# FindCalendarEventParticipantDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CalendarEventParticipant]**](CalendarEventParticipant.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_calendar_event_participant_duplicates_request import FindCalendarEventParticipantDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindCalendarEventParticipantDuplicatesRequest from a JSON string
find_calendar_event_participant_duplicates_request_instance = FindCalendarEventParticipantDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindCalendarEventParticipantDuplicatesRequest.to_json())

# convert the object into a dict
find_calendar_event_participant_duplicates_request_dict = find_calendar_event_participant_duplicates_request_instance.to_dict()
# create an instance of FindCalendarEventParticipantDuplicatesRequest from a dict
find_calendar_event_participant_duplicates_request_from_dict = FindCalendarEventParticipantDuplicatesRequest.from_dict(find_calendar_event_participant_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


