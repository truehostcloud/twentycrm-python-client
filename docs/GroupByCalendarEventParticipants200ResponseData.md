# GroupByCalendarEventParticipants200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**calendar_event_participants_group_by** | [**List[GroupByCalendarEventParticipants200ResponseDataCalendarEventParticipantsGroupByInner]**](GroupByCalendarEventParticipants200ResponseDataCalendarEventParticipantsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_calendar_event_participants200_response_data import GroupByCalendarEventParticipants200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByCalendarEventParticipants200ResponseData from a JSON string
group_by_calendar_event_participants200_response_data_instance = GroupByCalendarEventParticipants200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByCalendarEventParticipants200ResponseData.to_json())

# convert the object into a dict
group_by_calendar_event_participants200_response_data_dict = group_by_calendar_event_participants200_response_data_instance.to_dict()
# create an instance of GroupByCalendarEventParticipants200ResponseData from a dict
group_by_calendar_event_participants200_response_data_from_dict = GroupByCalendarEventParticipants200ResponseData.from_dict(group_by_calendar_event_participants200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


