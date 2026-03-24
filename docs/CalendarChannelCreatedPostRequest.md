# CalendarChannelCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**CalendarChannelCreatedPostRequestObjectMetadata**](CalendarChannelCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**CalendarChannelForResponse**](CalendarChannelForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_channel_created_post_request import CalendarChannelCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelCreatedPostRequest from a JSON string
calendar_channel_created_post_request_instance = CalendarChannelCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelCreatedPostRequest.to_json())

# convert the object into a dict
calendar_channel_created_post_request_dict = calendar_channel_created_post_request_instance.to_dict()
# create an instance of CalendarChannelCreatedPostRequest from a dict
calendar_channel_created_post_request_from_dict = CalendarChannelCreatedPostRequest.from_dict(calendar_channel_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


