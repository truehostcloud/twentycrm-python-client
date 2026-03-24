# UpdateManyCalendarChannels200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**update_calendar_channels** | [**List[CalendarChannelForResponse]**](CalendarChannelForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.update_many_calendar_channels200_response_data import UpdateManyCalendarChannels200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateManyCalendarChannels200ResponseData from a JSON string
update_many_calendar_channels200_response_data_instance = UpdateManyCalendarChannels200ResponseData.from_json(json)
# print the JSON string representation of the object
print(UpdateManyCalendarChannels200ResponseData.to_json())

# convert the object into a dict
update_many_calendar_channels200_response_data_dict = update_many_calendar_channels200_response_data_instance.to_dict()
# create an instance of UpdateManyCalendarChannels200ResponseData from a dict
update_many_calendar_channels200_response_data_from_dict = UpdateManyCalendarChannels200ResponseData.from_dict(update_many_calendar_channels200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


