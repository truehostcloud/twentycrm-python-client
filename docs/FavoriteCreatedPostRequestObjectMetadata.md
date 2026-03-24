# FavoriteCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.favorite_created_post_request_object_metadata import FavoriteCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteCreatedPostRequestObjectMetadata from a JSON string
favorite_created_post_request_object_metadata_instance = FavoriteCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(FavoriteCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
favorite_created_post_request_object_metadata_dict = favorite_created_post_request_object_metadata_instance.to_dict()
# create an instance of FavoriteCreatedPostRequestObjectMetadata from a dict
favorite_created_post_request_object_metadata_from_dict = FavoriteCreatedPostRequestObjectMetadata.from_dict(favorite_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


