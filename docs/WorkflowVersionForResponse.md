# WorkflowVersionForResponse

A workflow version

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | **str** | The workflow version name | [optional] 
**trigger** | **object** | Json object to provide trigger | [optional] 
**steps** | **object** | Json object to provide steps | [optional] 
**status** | **str** | The workflow version status | [optional] 
**position** | **float** | Workflow version position | [optional] 
**workflow_id** | **UUID** |  | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the workflow version | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline activities linked to the version | [optional] 
**workflow** | [**WorkflowForResponse**](WorkflowForResponse.md) |  | [optional] 
**runs** | [**List[WorkflowRunForResponse]**](WorkflowRunForResponse.md) | Workflow runs linked to the version. | [optional] 

## Example

```python
from twentycrm_client.models.workflow_version_for_response import WorkflowVersionForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowVersionForResponse from a JSON string
workflow_version_for_response_instance = WorkflowVersionForResponse.from_json(json)
# print the JSON string representation of the object
print(WorkflowVersionForResponse.to_json())

# convert the object into a dict
workflow_version_for_response_dict = workflow_version_for_response_instance.to_dict()
# create an instance of WorkflowVersionForResponse from a dict
workflow_version_for_response_from_dict = WorkflowVersionForResponse.from_dict(workflow_version_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


