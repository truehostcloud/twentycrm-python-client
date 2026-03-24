# MessageChannelUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**MessageChannelCreatedPostRequestObjectMetadata**](MessageChannelCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**MessageChannelForResponse**](MessageChannelForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_channel_updated_post_request import MessageChannelUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of MessageChannelUpdatedPostRequest from a JSON string
message_channel_updated_post_request_instance = MessageChannelUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(MessageChannelUpdatedPostRequest.to_json())

# convert the object into a dict
message_channel_updated_post_request_dict = message_channel_updated_post_request_instance.to_dict()
# create an instance of MessageChannelUpdatedPostRequest from a dict
message_channel_updated_post_request_from_dict = MessageChannelUpdatedPostRequest.from_dict(message_channel_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


