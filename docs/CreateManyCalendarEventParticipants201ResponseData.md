# CreateManyCalendarEventParticipants201ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_calendar_event_participants** | [**List[CalendarEventParticipantForResponse]**](CalendarEventParticipantForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_many_calendar_event_participants201_response_data import CreateManyCalendarEventParticipants201ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of CreateManyCalendarEventParticipants201ResponseData from a JSON string
create_many_calendar_event_participants201_response_data_instance = CreateManyCalendarEventParticipants201ResponseData.from_json(json)
# print the JSON string representation of the object
print(CreateManyCalendarEventParticipants201ResponseData.to_json())

# convert the object into a dict
create_many_calendar_event_participants201_response_data_dict = create_many_calendar_event_participants201_response_data_instance.to_dict()
# create an instance of CreateManyCalendarEventParticipants201ResponseData from a dict
create_many_calendar_event_participants201_response_data_from_dict = CreateManyCalendarEventParticipants201ResponseData.from_dict(create_many_calendar_event_participants201_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


