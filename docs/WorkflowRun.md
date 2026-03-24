# WorkflowRun

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
**state** | **object** | State of the workflow run | 
**context** | **object** | Context of the workflow run | [optional] 
**output** | **object** | Output of the workflow run | [optional] 
**position** | **float** | Workflow run position | [optional] 
**workflow_id** | **UUID** |  | [optional] 
**workflow_version_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_run import WorkflowRun

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowRun from a JSON string
workflow_run_instance = WorkflowRun.from_json(json)
# print the JSON string representation of the object
print(WorkflowRun.to_json())

# convert the object into a dict
workflow_run_dict = workflow_run_instance.to_dict()
# create an instance of WorkflowRun from a dict
workflow_run_from_dict = WorkflowRun.from_dict(workflow_run_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


