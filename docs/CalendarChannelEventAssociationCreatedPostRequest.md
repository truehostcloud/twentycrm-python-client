# CalendarChannelEventAssociationCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**CalendarChannelEventAssociationCreatedPostRequestObjectMetadata**](CalendarChannelEventAssociationCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**CalendarChannelEventAssociationForResponse**](CalendarChannelEventAssociationForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_channel_event_association_created_post_request import CalendarChannelEventAssociationCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelEventAssociationCreatedPostRequest from a JSON string
calendar_channel_event_association_created_post_request_instance = CalendarChannelEventAssociationCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelEventAssociationCreatedPostRequest.to_json())

# convert the object into a dict
calendar_channel_event_association_created_post_request_dict = calendar_channel_event_association_created_post_request_instance.to_dict()
# create an instance of CalendarChannelEventAssociationCreatedPostRequest from a dict
calendar_channel_event_association_created_post_request_from_dict = CalendarChannelEventAssociationCreatedPostRequest.from_dict(calendar_channel_event_association_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


