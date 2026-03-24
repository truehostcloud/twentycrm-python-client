# WorkflowCreatedPostRequest


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
from twentycrm_client.models.workflow_created_post_request import WorkflowCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowCreatedPostRequest from a JSON string
workflow_created_post_request_instance = WorkflowCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(WorkflowCreatedPostRequest.to_json())

# convert the object into a dict
workflow_created_post_request_dict = workflow_created_post_request_instance.to_dict()
# create an instance of WorkflowCreatedPostRequest from a dict
workflow_created_post_request_from_dict = WorkflowCreatedPostRequest.from_dict(workflow_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


