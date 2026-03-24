# FindCalendarEventDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CalendarEvent]**](CalendarEvent.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_calendar_event_duplicates_request import FindCalendarEventDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindCalendarEventDuplicatesRequest from a JSON string
find_calendar_event_duplicates_request_instance = FindCalendarEventDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindCalendarEventDuplicatesRequest.to_json())

# convert the object into a dict
find_calendar_event_duplicates_request_dict = find_calendar_event_duplicates_request_instance.to_dict()
# create an instance of FindCalendarEventDuplicatesRequest from a dict
find_calendar_event_duplicates_request_from_dict = FindCalendarEventDuplicatesRequest.from_dict(find_calendar_event_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


