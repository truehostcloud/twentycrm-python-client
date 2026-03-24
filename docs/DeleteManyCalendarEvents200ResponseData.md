# DeleteManyCalendarEvents200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delete_calendar_events** | [**List[DeleteManyAttachments200ResponseDataDeleteAttachmentsInner]**](DeleteManyAttachments200ResponseDataDeleteAttachmentsInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_calendar_events200_response_data import DeleteManyCalendarEvents200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyCalendarEvents200ResponseData from a JSON string
delete_many_calendar_events200_response_data_instance = DeleteManyCalendarEvents200ResponseData.from_json(json)
# print the JSON string representation of the object
print(DeleteManyCalendarEvents200ResponseData.to_json())

# convert the object into a dict
delete_many_calendar_events200_response_data_dict = delete_many_calendar_events200_response_data_instance.to_dict()
# create an instance of DeleteManyCalendarEvents200ResponseData from a dict
delete_many_calendar_events200_response_data_from_dict = DeleteManyCalendarEvents200ResponseData.from_dict(delete_many_calendar_events200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


