# FavoriteFolderForUpdate

A favorite folder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**position** | **int** | Favorite folder position | [optional] 
**name** | **str** | Name of the favorite folder | [optional] 

## Example

```python
from twentycrm_client.models.favorite_folder_for_update import FavoriteFolderForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteFolderForUpdate from a JSON string
favorite_folder_for_update_instance = FavoriteFolderForUpdate.from_json(json)
# print the JSON string representation of the object
print(FavoriteFolderForUpdate.to_json())

# convert the object into a dict
favorite_folder_for_update_dict = favorite_folder_for_update_instance.to_dict()
# create an instance of FavoriteFolderForUpdate from a dict
favorite_folder_for_update_from_dict = FavoriteFolderForUpdate.from_dict(favorite_folder_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


