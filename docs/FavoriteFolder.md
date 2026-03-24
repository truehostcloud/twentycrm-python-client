# FavoriteFolder

A favorite folder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**position** | **int** | Favorite folder position | [optional] 
**name** | **str** | Name of the favorite folder | [optional] 

## Example

```python
from twentycrm_client.models.favorite_folder import FavoriteFolder

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteFolder from a JSON string
favorite_folder_instance = FavoriteFolder.from_json(json)
# print the JSON string representation of the object
print(FavoriteFolder.to_json())

# convert the object into a dict
favorite_folder_dict = favorite_folder_instance.to_dict()
# create an instance of FavoriteFolder from a dict
favorite_folder_from_dict = FavoriteFolder.from_dict(favorite_folder_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


