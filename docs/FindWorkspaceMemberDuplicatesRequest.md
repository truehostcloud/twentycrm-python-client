# FindWorkspaceMemberDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[WorkspaceMember]**](WorkspaceMember.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_workspace_member_duplicates_request import FindWorkspaceMemberDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindWorkspaceMemberDuplicatesRequest from a JSON string
find_workspace_member_duplicates_request_instance = FindWorkspaceMemberDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindWorkspaceMemberDuplicatesRequest.to_json())

# convert the object into a dict
find_workspace_member_duplicates_request_dict = find_workspace_member_duplicates_request_instance.to_dict()
# create an instance of FindWorkspaceMemberDuplicatesRequest from a dict
find_workspace_member_duplicates_request_from_dict = FindWorkspaceMemberDuplicatesRequest.from_dict(find_workspace_member_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


