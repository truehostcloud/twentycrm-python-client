# Favorite

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
from twentycrm_client.models.favorite import Favorite

# TODO update the JSON string below
json = "{}"
# create an instance of Favorite from a JSON string
favorite_instance = Favorite.from_json(json)
# print the JSON string representation of the object
print(Favorite.to_json())

# convert the object into a dict
favorite_dict = favorite_instance.to_dict()
# create an instance of Favorite from a dict
favorite_from_dict = Favorite.from_dict(favorite_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


