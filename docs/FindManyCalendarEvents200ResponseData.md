# FindManyCalendarEvents200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**calendar_events** | [**List[CalendarEventForResponse]**](CalendarEventForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_calendar_events200_response_data import FindManyCalendarEvents200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyCalendarEvents200ResponseData from a JSON string
find_many_calendar_events200_response_data_instance = FindManyCalendarEvents200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindManyCalendarEvents200ResponseData.to_json())

# convert the object into a dict
find_many_calendar_events200_response_data_dict = find_many_calendar_events200_response_data_instance.to_dict()
# create an instance of FindManyCalendarEvents200ResponseData from a dict
find_many_calendar_events200_response_data_from_dict = FindManyCalendarEvents200ResponseData.from_dict(find_many_calendar_events200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


