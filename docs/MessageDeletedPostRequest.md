# MessageDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**MessageCreatedPostRequestObjectMetadata**](MessageCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**MessageForResponse**](MessageForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.message_deleted_post_request import MessageDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of MessageDeletedPostRequest from a JSON string
message_deleted_post_request_instance = MessageDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(MessageDeletedPostRequest.to_json())

# convert the object into a dict
message_deleted_post_request_dict = message_deleted_post_request_instance.to_dict()
# create an instance of MessageDeletedPostRequest from a dict
message_deleted_post_request_from_dict = MessageDeletedPostRequest.from_dict(message_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


