# FavoriteFolderForResponse

A favorite folder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**position** | **int** | Favorite folder position | [optional] 
**name** | **str** | Name of the favorite folder | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites in this folder | [optional] 

## Example

```python
from twentycrm_client.models.favorite_folder_for_response import FavoriteFolderForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteFolderForResponse from a JSON string
favorite_folder_for_response_instance = FavoriteFolderForResponse.from_json(json)
# print the JSON string representation of the object
print(FavoriteFolderForResponse.to_json())

# convert the object into a dict
favorite_folder_for_response_dict = favorite_folder_for_response_instance.to_dict()
# create an instance of FavoriteFolderForResponse from a dict
favorite_folder_for_response_from_dict = FavoriteFolderForResponse.from_dict(favorite_folder_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


