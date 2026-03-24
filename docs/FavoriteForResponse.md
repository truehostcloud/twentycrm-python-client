# FavoriteForResponse

A favorite

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
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
**company** | [**CompanyForResponse**](CompanyForResponse.md) |  | [optional] 
**dashboard** | [**DashboardForResponse**](DashboardForResponse.md) |  | [optional] 
**for_workspace_member** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 
**person** | [**PersonForResponse**](PersonForResponse.md) |  | [optional] 
**opportunity** | [**OpportunityForResponse**](OpportunityForResponse.md) |  | [optional] 
**workflow** | [**WorkflowForResponse**](WorkflowForResponse.md) |  | [optional] 
**workflow_version** | [**WorkflowVersionForResponse**](WorkflowVersionForResponse.md) |  | [optional] 
**workflow_run** | [**WorkflowRunForResponse**](WorkflowRunForResponse.md) |  | [optional] 
**task** | [**TaskForResponse**](TaskForResponse.md) |  | [optional] 
**note** | [**NoteForResponse**](NoteForResponse.md) |  | [optional] 
**favorite_folder** | [**FavoriteFolderForResponse**](FavoriteFolderForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.favorite_for_response import FavoriteForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of FavoriteForResponse from a JSON string
favorite_for_response_instance = FavoriteForResponse.from_json(json)
# print the JSON string representation of the object
print(FavoriteForResponse.to_json())

# convert the object into a dict
favorite_for_response_dict = favorite_for_response_instance.to_dict()
# create an instance of FavoriteForResponse from a dict
favorite_for_response_from_dict = FavoriteForResponse.from_dict(favorite_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


