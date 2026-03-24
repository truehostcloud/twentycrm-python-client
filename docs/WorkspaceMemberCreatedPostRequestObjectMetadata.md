# WorkspaceMemberCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.workspace_member_created_post_request_object_metadata import WorkspaceMemberCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of WorkspaceMemberCreatedPostRequestObjectMetadata from a JSON string
workspace_member_created_post_request_object_metadata_instance = WorkspaceMemberCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(WorkspaceMemberCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
workspace_member_created_post_request_object_metadata_dict = workspace_member_created_post_request_object_metadata_instance.to_dict()
# create an instance of WorkspaceMemberCreatedPostRequestObjectMetadata from a dict
workspace_member_created_post_request_object_metadata_from_dict = WorkspaceMemberCreatedPostRequestObjectMetadata.from_dict(workspace_member_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


