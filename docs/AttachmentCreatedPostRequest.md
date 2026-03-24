# AttachmentCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**AttachmentCreatedPostRequestObjectMetadata**](AttachmentCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**AttachmentForResponse**](AttachmentForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.attachment_created_post_request import AttachmentCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AttachmentCreatedPostRequest from a JSON string
attachment_created_post_request_instance = AttachmentCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(AttachmentCreatedPostRequest.to_json())

# convert the object into a dict
attachment_created_post_request_dict = attachment_created_post_request_instance.to_dict()
# create an instance of AttachmentCreatedPostRequest from a dict
attachment_created_post_request_from_dict = AttachmentCreatedPostRequest.from_dict(attachment_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


