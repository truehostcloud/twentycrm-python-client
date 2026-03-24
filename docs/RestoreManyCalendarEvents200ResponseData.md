# RestoreManyCalendarEvents200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**restore_calendar_events** | [**List[CalendarEventForResponse]**](CalendarEventForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_many_calendar_events200_response_data import RestoreManyCalendarEvents200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreManyCalendarEvents200ResponseData from a JSON string
restore_many_calendar_events200_response_data_instance = RestoreManyCalendarEvents200ResponseData.from_json(json)
# print the JSON string representation of the object
print(RestoreManyCalendarEvents200ResponseData.to_json())

# convert the object into a dict
restore_many_calendar_events200_response_data_dict = restore_many_calendar_events200_response_data_instance.to_dict()
# create an instance of RestoreManyCalendarEvents200ResponseData from a dict
restore_many_calendar_events200_response_data_from_dict = RestoreManyCalendarEvents200ResponseData.from_dict(restore_many_calendar_events200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


