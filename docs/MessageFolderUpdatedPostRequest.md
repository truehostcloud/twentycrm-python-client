# MessageFolderUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**MessageFolderCreatedPostRequestObjectMetadata**](MessageFolderCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**MessageFolderForResponse**](MessageFolderForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_folder_updated_post_request import MessageFolderUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of MessageFolderUpdatedPostRequest from a JSON string
message_folder_updated_post_request_instance = MessageFolderUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(MessageFolderUpdatedPostRequest.to_json())

# convert the object into a dict
message_folder_updated_post_request_dict = message_folder_updated_post_request_instance.to_dict()
# create an instance of MessageFolderUpdatedPostRequest from a dict
message_folder_updated_post_request_from_dict = MessageFolderUpdatedPostRequest.from_dict(message_folder_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


