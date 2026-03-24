# WorkflowDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**WorkflowCreatedPostRequestObjectMetadata**](WorkflowCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**WorkflowForResponse**](WorkflowForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_deleted_post_request import WorkflowDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowDeletedPostRequest from a JSON string
workflow_deleted_post_request_instance = WorkflowDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(WorkflowDeletedPostRequest.to_json())

# convert the object into a dict
workflow_deleted_post_request_dict = workflow_deleted_post_request_instance.to_dict()
# create an instance of WorkflowDeletedPostRequest from a dict
workflow_deleted_post_request_from_dict = WorkflowDeletedPostRequest.from_dict(workflow_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


