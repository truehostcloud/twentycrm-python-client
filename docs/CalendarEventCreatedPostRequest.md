# CalendarEventCreatedPostRequest


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
from twentycrm_client.models.calendar_event_created_post_request import CalendarEventCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventCreatedPostRequest from a JSON string
calendar_event_created_post_request_instance = CalendarEventCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CalendarEventCreatedPostRequest.to_json())

# convert the object into a dict
calendar_event_created_post_request_dict = calendar_event_created_post_request_instance.to_dict()
# create an instance of CalendarEventCreatedPostRequest from a dict
calendar_event_created_post_request_from_dict = CalendarEventCreatedPostRequest.from_dict(calendar_event_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


