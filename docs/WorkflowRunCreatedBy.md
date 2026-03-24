# WorkflowRunCreatedBy

The executor of the workflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.workflow_run_created_by import WorkflowRunCreatedBy

# TODO update the JSON string below
json = "{}"
# create an instance of WorkflowRunCreatedBy from a JSON string
workflow_run_created_by_instance = WorkflowRunCreatedBy.from_json(json)
# print the JSON string representation of the object
print(WorkflowRunCreatedBy.to_json())

# convert the object into a dict
workflow_run_created_by_dict = workflow_run_created_by_instance.to_dict()
# create an instance of WorkflowRunCreatedBy from a dict
workflow_run_created_by_from_dict = WorkflowRunCreatedBy.from_dict(workflow_run_created_by_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


