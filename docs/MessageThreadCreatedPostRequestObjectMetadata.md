# MessageThreadCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_thread_created_post_request_object_metadata import MessageThreadCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of MessageThreadCreatedPostRequestObjectMetadata from a JSON string
message_thread_created_post_request_object_metadata_instance = MessageThreadCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(MessageThreadCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
message_thread_created_post_request_object_metadata_dict = message_thread_created_post_request_object_metadata_instance.to_dict()
# create an instance of MessageThreadCreatedPostRequestObjectMetadata from a dict
message_thread_created_post_request_object_metadata_from_dict = MessageThreadCreatedPostRequestObjectMetadata.from_dict(message_thread_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


