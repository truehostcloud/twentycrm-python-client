# CalendarChannelUpdatedPostRequest


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
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_channel_updated_post_request import CalendarChannelUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelUpdatedPostRequest from a JSON string
calendar_channel_updated_post_request_instance = CalendarChannelUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelUpdatedPostRequest.to_json())

# convert the object into a dict
calendar_channel_updated_post_request_dict = calendar_channel_updated_post_request_instance.to_dict()
# create an instance of CalendarChannelUpdatedPostRequest from a dict
calendar_channel_updated_post_request_from_dict = CalendarChannelUpdatedPostRequest.from_dict(calendar_channel_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


