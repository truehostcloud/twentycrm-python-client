# WorkflowRunForResponseCreatedBy

The executor of the workflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_run_for_response_created_by import WorkflowRunForResponseCreatedBy

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowRunForResponseCreatedBy from a JSON string
workflow_run_for_response_created_by_instance = WorkflowRunForResponseCreatedBy.from_json(json)
# print the JSON string representation of the object
print(WorkflowRunForResponseCreatedBy.to_json())

# convert the object into a dict
workflow_run_for_response_created_by_dict = workflow_run_for_response_created_by_instance.to_dict()
# create an instance of WorkflowRunForResponseCreatedBy from a dict
workflow_run_for_response_created_by_from_dict = WorkflowRunForResponseCreatedBy.from_dict(workflow_run_for_response_created_by_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


