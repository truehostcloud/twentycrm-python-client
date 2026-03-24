# WorkflowVersionUpdatedPostRequest


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
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_version_updated_post_request import WorkflowVersionUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowVersionUpdatedPostRequest from a JSON string
workflow_version_updated_post_request_instance = WorkflowVersionUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(WorkflowVersionUpdatedPostRequest.to_json())

# convert the object into a dict
workflow_version_updated_post_request_dict = workflow_version_updated_post_request_instance.to_dict()
# create an instance of WorkflowVersionUpdatedPostRequest from a dict
workflow_version_updated_post_request_from_dict = WorkflowVersionUpdatedPostRequest.from_dict(workflow_version_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


