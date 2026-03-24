# DeleteManyCalendarEvents200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**DeleteManyCalendarEvents200ResponseData**](DeleteManyCalendarEvents200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_calendar_events200_response import DeleteManyCalendarEvents200Response

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyCalendarEvents200Response from a JSON string
delete_many_calendar_events200_response_instance = DeleteManyCalendarEvents200Response.from_json(json)
# print the JSON string representation of the object
print(DeleteManyCalendarEvents200Response.to_json())

# convert the object into a dict
delete_many_calendar_events200_response_dict = delete_many_calendar_events200_response_instance.to_dict()
# create an instance of DeleteManyCalendarEvents200Response from a dict
delete_many_calendar_events200_response_from_dict = DeleteManyCalendarEvents200Response.from_dict(delete_many_calendar_events200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


