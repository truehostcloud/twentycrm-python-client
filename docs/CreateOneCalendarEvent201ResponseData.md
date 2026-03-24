# CreateOneCalendarEvent201ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_calendar_event** | [**CalendarEventForResponse**](CalendarEventForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_one_calendar_event201_response_data import CreateOneCalendarEvent201ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of CreateOneCalendarEvent201ResponseData from a JSON string
create_one_calendar_event201_response_data_instance = CreateOneCalendarEvent201ResponseData.from_json(json)
# print the JSON string representation of the object
print(CreateOneCalendarEvent201ResponseData.to_json())

# convert the object into a dict
create_one_calendar_event201_response_data_dict = create_one_calendar_event201_response_data_instance.to_dict()
# create an instance of CreateOneCalendarEvent201ResponseData from a dict
create_one_calendar_event201_response_data_from_dict = CreateOneCalendarEvent201ResponseData.from_dict(create_one_calendar_event201_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


