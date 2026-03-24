# MessageChannelCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_channel_created_post_request_object_metadata import MessageChannelCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of MessageChannelCreatedPostRequestObjectMetadata from a JSON string
message_channel_created_post_request_object_metadata_instance = MessageChannelCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(MessageChannelCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
message_channel_created_post_request_object_metadata_dict = message_channel_created_post_request_object_metadata_instance.to_dict()
# create an instance of MessageChannelCreatedPostRequestObjectMetadata from a dict
message_channel_created_post_request_object_metadata_from_dict = MessageChannelCreatedPostRequestObjectMetadata.from_dict(message_channel_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


