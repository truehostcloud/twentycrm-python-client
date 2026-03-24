# FindFavoriteFolderDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[FavoriteFolder]**](FavoriteFolder.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_favorite_folder_duplicates_request import FindFavoriteFolderDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindFavoriteFolderDuplicatesRequest from a JSON string
find_favorite_folder_duplicates_request_instance = FindFavoriteFolderDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindFavoriteFolderDuplicatesRequest.to_json())

# convert the object into a dict
find_favorite_folder_duplicates_request_dict = find_favorite_folder_duplicates_request_instance.to_dict()
# create an instance of FindFavoriteFolderDuplicatesRequest from a dict
find_favorite_folder_duplicates_request_from_dict = FindFavoriteFolderDuplicatesRequest.from_dict(find_favorite_folder_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


