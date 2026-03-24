# WorkflowForResponse

A workflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | **str** | The workflow name | [optional] 
**last_published_version_id** | **str** | The workflow last published version id | [optional] 
**statuses** | **List[str]** | The current statuses of the workflow versions | [optional] 
**position** | **float** | Workflow record position | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**attachments** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Attachments linked to the workflow | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the workflow | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline activities linked to the workflow | [optional] 
**versions** | [**List[WorkflowVersionForResponse]**](WorkflowVersionForResponse.md) | Workflow versions linked to the workflow. | [optional] 
**runs** | [**List[WorkflowRunForResponse]**](WorkflowRunForResponse.md) | Workflow runs linked to the workflow. | [optional] 
**automated_triggers** | [**List[WorkflowAutomatedTriggerForResponse]**](WorkflowAutomatedTriggerForResponse.md) | Workflow automated triggers linked to the workflow. | [optional] 

## Example

```python
from twentycrm_client.models.workflow_for_response import WorkflowForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowForResponse from a JSON string
workflow_for_response_instance = WorkflowForResponse.from_json(json)
# print the JSON string representation of the object
print(WorkflowForResponse.to_json())

# convert the object into a dict
workflow_for_response_dict = workflow_for_response_instance.to_dict()
# create an instance of WorkflowForResponse from a dict
workflow_for_response_from_dict = WorkflowForResponse.from_dict(workflow_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


