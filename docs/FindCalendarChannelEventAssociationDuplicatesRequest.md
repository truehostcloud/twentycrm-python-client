# FindCalendarChannelEventAssociationDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CalendarChannelEventAssociation]**](CalendarChannelEventAssociation.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_calendar_channel_event_association_duplicates_request import FindCalendarChannelEventAssociationDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindCalendarChannelEventAssociationDuplicatesRequest from a JSON string
find_calendar_channel_event_association_duplicates_request_instance = FindCalendarChannelEventAssociationDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindCalendarChannelEventAssociationDuplicatesRequest.to_json())

# convert the object into a dict
find_calendar_channel_event_association_duplicates_request_dict = find_calendar_channel_event_association_duplicates_request_instance.to_dict()
# create an instance of FindCalendarChannelEventAssociationDuplicatesRequest from a dict
find_calendar_channel_event_association_duplicates_request_from_dict = FindCalendarChannelEventAssociationDuplicatesRequest.from_dict(find_calendar_channel_event_association_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


