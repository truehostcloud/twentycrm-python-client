# FavoriteFolderDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**FavoriteFolderCreatedPostRequestObjectMetadata**](FavoriteFolderCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**FavoriteFolderForResponse**](FavoriteFolderForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.favorite_folder_deleted_post_request import FavoriteFolderDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteFolderDeletedPostRequest from a JSON string
favorite_folder_deleted_post_request_instance = FavoriteFolderDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(FavoriteFolderDeletedPostRequest.to_json())

# convert the object into a dict
favorite_folder_deleted_post_request_dict = favorite_folder_deleted_post_request_instance.to_dict()
# create an instance of FavoriteFolderDeletedPostRequest from a dict
favorite_folder_deleted_post_request_from_dict = FavoriteFolderDeletedPostRequest.from_dict(favorite_folder_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


