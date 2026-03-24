# WorkflowRunDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**WorkflowRunCreatedPostRequestObjectMetadata**](WorkflowRunCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**WorkflowRunForResponse**](WorkflowRunForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_run_deleted_post_request import WorkflowRunDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowRunDeletedPostRequest from a JSON string
workflow_run_deleted_post_request_instance = WorkflowRunDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(WorkflowRunDeletedPostRequest.to_json())

# convert the object into a dict
workflow_run_deleted_post_request_dict = workflow_run_deleted_post_request_instance.to_dict()
# create an instance of WorkflowRunDeletedPostRequest from a dict
workflow_run_deleted_post_request_from_dict = WorkflowRunDeletedPostRequest.from_dict(workflow_run_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


