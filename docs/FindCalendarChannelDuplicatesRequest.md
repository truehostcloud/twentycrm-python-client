# FindCalendarChannelDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CalendarChannel]**](CalendarChannel.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_calendar_channel_duplicates_request import FindCalendarChannelDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindCalendarChannelDuplicatesRequest from a JSON string
find_calendar_channel_duplicates_request_instance = FindCalendarChannelDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindCalendarChannelDuplicatesRequest.to_json())

# convert the object into a dict
find_calendar_channel_duplicates_request_dict = find_calendar_channel_duplicates_request_instance.to_dict()
# create an instance of FindCalendarChannelDuplicatesRequest from a dict
find_calendar_channel_duplicates_request_from_dict = FindCalendarChannelDuplicatesRequest.from_dict(find_calendar_channel_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


