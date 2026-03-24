# CalendarEventDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**CalendarEventCreatedPostRequestObjectMetadata**](CalendarEventCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**CalendarEventForResponse**](CalendarEventForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_deleted_post_request import CalendarEventDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventDeletedPostRequest from a JSON string
calendar_event_deleted_post_request_instance = CalendarEventDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CalendarEventDeletedPostRequest.to_json())

# convert the object into a dict
calendar_event_deleted_post_request_dict = calendar_event_deleted_post_request_instance.to_dict()
# create an instance of CalendarEventDeletedPostRequest from a dict
calendar_event_deleted_post_request_from_dict = CalendarEventDeletedPostRequest.from_dict(calendar_event_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


