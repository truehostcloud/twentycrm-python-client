# WorkspaceMemberDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**WorkspaceMemberCreatedPostRequestObjectMetadata**](WorkspaceMemberCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.workspace_member_deleted_post_request import WorkspaceMemberDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of WorkspaceMemberDeletedPostRequest from a JSON string
workspace_member_deleted_post_request_instance = WorkspaceMemberDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(WorkspaceMemberDeletedPostRequest.to_json())

# convert the object into a dict
workspace_member_deleted_post_request_dict = workspace_member_deleted_post_request_instance.to_dict()
# create an instance of WorkspaceMemberDeletedPostRequest from a dict
workspace_member_deleted_post_request_from_dict = WorkspaceMemberDeletedPostRequest.from_dict(workspace_member_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


