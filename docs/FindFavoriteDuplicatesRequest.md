# FindFavoriteDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Favorite]**](Favorite.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_favorite_duplicates_request import FindFavoriteDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindFavoriteDuplicatesRequest from a JSON string
find_favorite_duplicates_request_instance = FindFavoriteDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindFavoriteDuplicatesRequest.to_json())

# convert the object into a dict
find_favorite_duplicates_request_dict = find_favorite_duplicates_request_instance.to_dict()
# create an instance of FindFavoriteDuplicatesRequest from a dict
find_favorite_duplicates_request_from_dict = FindFavoriteDuplicatesRequest.from_dict(find_favorite_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


