# WorkflowVersionCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**WorkflowVersionCreatedPostRequestObjectMetadata**](WorkflowVersionCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**WorkflowVersionForResponse**](WorkflowVersionForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_version_created_post_request import WorkflowVersionCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowVersionCreatedPostRequest from a JSON string
workflow_version_created_post_request_instance = WorkflowVersionCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(WorkflowVersionCreatedPostRequest.to_json())

# convert the object into a dict
workflow_version_created_post_request_dict = workflow_version_created_post_request_instance.to_dict()
# create an instance of WorkflowVersionCreatedPostRequest from a dict
workflow_version_created_post_request_from_dict = WorkflowVersionCreatedPostRequest.from_dict(workflow_version_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


