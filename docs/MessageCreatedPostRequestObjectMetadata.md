# MessageCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_created_post_request_object_metadata import MessageCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of MessageCreatedPostRequestObjectMetadata from a JSON string
message_created_post_request_object_metadata_instance = MessageCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(MessageCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
message_created_post_request_object_metadata_dict = message_created_post_request_object_metadata_instance.to_dict()
# create an instance of MessageCreatedPostRequestObjectMetadata from a dict
message_created_post_request_object_metadata_from_dict = MessageCreatedPostRequestObjectMetadata.from_dict(message_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


