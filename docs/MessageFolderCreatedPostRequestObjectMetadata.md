# MessageFolderCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_folder_created_post_request_object_metadata import MessageFolderCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of MessageFolderCreatedPostRequestObjectMetadata from a JSON string
message_folder_created_post_request_object_metadata_instance = MessageFolderCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(MessageFolderCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
message_folder_created_post_request_object_metadata_dict = message_folder_created_post_request_object_metadata_instance.to_dict()
# create an instance of MessageFolderCreatedPostRequestObjectMetadata from a dict
message_folder_created_post_request_object_metadata_from_dict = MessageFolderCreatedPostRequestObjectMetadata.from_dict(message_folder_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


