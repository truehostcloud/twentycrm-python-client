# DeleteManyCalendarChannelEventAssociations200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delete_calendar_channel_event_associations** | [**List[DeleteManyAttachments200ResponseDataDeleteAttachmentsInner]**](DeleteManyAttachments200ResponseDataDeleteAttachmentsInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_calendar_channel_event_associations200_response_data import DeleteManyCalendarChannelEventAssociations200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyCalendarChannelEventAssociations200ResponseData from a JSON string
delete_many_calendar_channel_event_associations200_response_data_instance = DeleteManyCalendarChannelEventAssociations200ResponseData.from_json(json)
# print the JSON string representation of the object
print(DeleteManyCalendarChannelEventAssociations200ResponseData.to_json())

# convert the object into a dict
delete_many_calendar_channel_event_associations200_response_data_dict = delete_many_calendar_channel_event_associations200_response_data_instance.to_dict()
# create an instance of DeleteManyCalendarChannelEventAssociations200ResponseData from a dict
delete_many_calendar_channel_event_associations200_response_data_from_dict = DeleteManyCalendarChannelEventAssociations200ResponseData.from_dict(delete_many_calendar_channel_event_associations200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


