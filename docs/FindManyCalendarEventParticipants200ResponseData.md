# FindManyCalendarEventParticipants200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**calendar_event_participants** | [**List[CalendarEventParticipantForResponse]**](CalendarEventParticipantForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_calendar_event_participants200_response_data import FindManyCalendarEventParticipants200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyCalendarEventParticipants200ResponseData from a JSON string
find_many_calendar_event_participants200_response_data_instance = FindManyCalendarEventParticipants200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindManyCalendarEventParticipants200ResponseData.to_json())

# convert the object into a dict
find_many_calendar_event_participants200_response_data_dict = find_many_calendar_event_participants200_response_data_instance.to_dict()
# create an instance of FindManyCalendarEventParticipants200ResponseData from a dict
find_many_calendar_event_participants200_response_data_from_dict = FindManyCalendarEventParticipants200ResponseData.from_dict(find_many_calendar_event_participants200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


