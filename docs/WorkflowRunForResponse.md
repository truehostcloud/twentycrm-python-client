# WorkflowRunForResponse

A workflow run

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | **str** | Name of the workflow run | [optional] 
**enqueued_at** | **datetime** | Workflow run enqueued at | [optional] 
**started_at** | **datetime** | Workflow run started at | [optional] 
**ended_at** | **datetime** | Workflow run ended at | [optional] 
**status** | **str** | Workflow run status | [optional] 
**created_by** | [**WorkflowRunForResponseCreatedBy**](WorkflowRunForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**state** | **object** | State of the workflow run | [optional] 
**context** | **object** | Context of the workflow run | [optional] 
**output** | **object** | Output of the workflow run | [optional] 
**position** | **float** | Workflow run position | [optional] 
**workflow_id** | **UUID** |  | [optional] 
**workflow_version_id** | **UUID** |  | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the workflow run | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline activities linked to the run | [optional] 
**workflow** | [**WorkflowForResponse**](WorkflowForResponse.md) |  | [optional] 
**workflow_version** | [**WorkflowVersionForResponse**](WorkflowVersionForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_run_for_response import WorkflowRunForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowRunForResponse from a JSON string
workflow_run_for_response_instance = WorkflowRunForResponse.from_json(json)
# print the JSON string representation of the object
print(WorkflowRunForResponse.to_json())

# convert the object into a dict
workflow_run_for_response_dict = workflow_run_for_response_instance.to_dict()
# create an instance of WorkflowRunForResponse from a dict
workflow_run_for_response_from_dict = WorkflowRunForResponse.from_dict(workflow_run_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


