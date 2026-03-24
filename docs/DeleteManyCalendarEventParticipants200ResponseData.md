# DeleteManyCalendarEventParticipants200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delete_calendar_event_participants** | [**List[DeleteManyAttachments200ResponseDataDeleteAttachmentsInner]**](DeleteManyAttachments200ResponseDataDeleteAttachmentsInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_calendar_event_participants200_response_data import DeleteManyCalendarEventParticipants200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyCalendarEventParticipants200ResponseData from a JSON string
delete_many_calendar_event_participants200_response_data_instance = DeleteManyCalendarEventParticipants200ResponseData.from_json(json)
# print the JSON string representation of the object
print(DeleteManyCalendarEventParticipants200ResponseData.to_json())

# convert the object into a dict
delete_many_calendar_event_participants200_response_data_dict = delete_many_calendar_event_participants200_response_data_instance.to_dict()
# create an instance of DeleteManyCalendarEventParticipants200ResponseData from a dict
delete_many_calendar_event_participants200_response_data_from_dict = DeleteManyCalendarEventParticipants200ResponseData.from_dict(delete_many_calendar_event_participants200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


