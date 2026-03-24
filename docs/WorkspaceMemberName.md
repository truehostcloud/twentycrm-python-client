# WorkspaceMemberName

Workspace member name

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_name** | **str** |  | [optional] 
**last_name** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.workspace_member_name import WorkspaceMemberName

# TODO update the JSON string below
json = "{}"
# create an instance of WorkspaceMemberName from a JSON string
workspace_member_name_instance = WorkspaceMemberName.from_json(json)
# print the JSON string representation of the object
print(WorkspaceMemberName.to_json())

# convert the object into a dict
workspace_member_name_dict = workspace_member_name_instance.to_dict()
# create an instance of WorkspaceMemberName from a dict
workspace_member_name_from_dict = WorkspaceMemberName.from_dict(workspace_member_name_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


