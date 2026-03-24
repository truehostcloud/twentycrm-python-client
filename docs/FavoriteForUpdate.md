# FavoriteForUpdate

A favorite

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**position** | **int** | Favorite position | [optional] 
**view_id** | **UUID** | ViewId | [optional] 
**company_id** | **UUID** |  | [optional] 
**dashboard_id** | **UUID** |  | [optional] 
**for_workspace_member_id** | **UUID** |  | [optional] 
**person_id** | **UUID** |  | [optional] 
**opportunity_id** | **UUID** |  | [optional] 
**workflow_id** | **UUID** |  | [optional] 
**workflow_version_id** | **UUID** |  | [optional] 
**workflow_run_id** | **UUID** |  | [optional] 
**task_id** | **UUID** |  | [optional] 
**note_id** | **UUID** |  | [optional] 
**favorite_folder_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.favorite_for_update import FavoriteForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteForUpdate from a JSON string
favorite_for_update_instance = FavoriteForUpdate.from_json(json)
# print the JSON string representation of the object
print(FavoriteForUpdate.to_json())

# convert the object into a dict
favorite_for_update_dict = favorite_for_update_instance.to_dict()
# create an instance of FavoriteForUpdate from a dict
favorite_for_update_from_dict = FavoriteForUpdate.from_dict(favorite_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


