# AttachmentCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.attachment_created_post_request_object_metadata import AttachmentCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of AttachmentCreatedPostRequestObjectMetadata from a JSON string
attachment_created_post_request_object_metadata_instance = AttachmentCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(AttachmentCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
attachment_created_post_request_object_metadata_dict = attachment_created_post_request_object_metadata_instance.to_dict()
# create an instance of AttachmentCreatedPostRequestObjectMetadata from a dict
attachment_created_post_request_object_metadata_from_dict = AttachmentCreatedPostRequestObjectMetadata.from_dict(attachment_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


