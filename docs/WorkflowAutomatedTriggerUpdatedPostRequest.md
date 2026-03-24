# WorkflowAutomatedTriggerUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**WorkflowAutomatedTriggerCreatedPostRequestObjectMetadata**](WorkflowAutomatedTriggerCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**WorkflowAutomatedTriggerForResponse**](WorkflowAutomatedTriggerForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_automated_trigger_updated_post_request import WorkflowAutomatedTriggerUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowAutomatedTriggerUpdatedPostRequest from a JSON string
workflow_automated_trigger_updated_post_request_instance = WorkflowAutomatedTriggerUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(WorkflowAutomatedTriggerUpdatedPostRequest.to_json())

# convert the object into a dict
workflow_automated_trigger_updated_post_request_dict = workflow_automated_trigger_updated_post_request_instance.to_dict()
# create an instance of WorkflowAutomatedTriggerUpdatedPostRequest from a dict
workflow_automated_trigger_updated_post_request_from_dict = WorkflowAutomatedTriggerUpdatedPostRequest.from_dict(workflow_automated_trigger_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


