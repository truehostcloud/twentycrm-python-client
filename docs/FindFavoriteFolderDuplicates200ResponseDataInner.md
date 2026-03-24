# FindFavoriteFolderDuplicates200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **float** |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**favorite_folder_duplicates** | [**List[FavoriteFolderForResponse]**](FavoriteFolderForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_favorite_folder_duplicates200_response_data_inner import FindFavoriteFolderDuplicates200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of FindFavoriteFolderDuplicates200ResponseDataInner from a JSON string
find_favorite_folder_duplicates200_response_data_inner_instance = FindFavoriteFolderDuplicates200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(FindFavoriteFolderDuplicates200ResponseDataInner.to_json())

# convert the object into a dict
find_favorite_folder_duplicates200_response_data_inner_dict = find_favorite_folder_duplicates200_response_data_inner_instance.to_dict()
# create an instance of FindFavoriteFolderDuplicates200ResponseDataInner from a dict
find_favorite_folder_duplicates200_response_data_inner_from_dict = FindFavoriteFolderDuplicates200ResponseDataInner.from_dict(find_favorite_folder_duplicates200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


