# WorkflowRunForUpdate

A workflow run

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the workflow run | [optional] 
**enqueued_at** | **datetime** | Workflow run enqueued at | [optional] 
**started_at** | **datetime** | Workflow run started at | [optional] 
**ended_at** | **datetime** | Workflow run ended at | [optional] 
**status** | **str** | Workflow run status | [optional] 
**created_by** | [**WorkflowRunCreatedBy**](WorkflowRunCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 
**state** | **object** | State of the workflow run | [optional] 
**context** | **object** | Context of the workflow run | [optional] 
**output** | **object** | Output of the workflow run | [optional] 
**position** | **float** | Workflow run position | [optional] 
**workflow_id** | **UUID** |  | [optional] 
**workflow_version_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_run_for_update import WorkflowRunForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowRunForUpdate from a JSON string
workflow_run_for_update_instance = WorkflowRunForUpdate.from_json(json)
# print the JSON string representation of the object
print(WorkflowRunForUpdate.to_json())

# convert the object into a dict
workflow_run_for_update_dict = workflow_run_for_update_instance.to_dict()
# create an instance of WorkflowRunForUpdate from a dict
workflow_run_for_update_from_dict = WorkflowRunForUpdate.from_dict(workflow_run_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


