# BlocklistCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.blocklist_created_post_request_object_metadata import BlocklistCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of BlocklistCreatedPostRequestObjectMetadata from a JSON string
blocklist_created_post_request_object_metadata_instance = BlocklistCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(BlocklistCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
blocklist_created_post_request_object_metadata_dict = blocklist_created_post_request_object_metadata_instance.to_dict()
# create an instance of BlocklistCreatedPostRequestObjectMetadata from a dict
blocklist_created_post_request_object_metadata_from_dict = BlocklistCreatedPostRequestObjectMetadata.from_dict(blocklist_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


