# CreateManyWorkflowRuns201ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_workflow_runs** | [**List[WorkflowRunForResponse]**](WorkflowRunForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.create_many_workflow_runs201_response_data import CreateManyWorkflowRuns201ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of CreateManyWorkflowRuns201ResponseData from a JSON string
create_many_workflow_runs201_response_data_instance = CreateManyWorkflowRuns201ResponseData.from_json(json)
# print the JSON string representation of the object
print(CreateManyWorkflowRuns201ResponseData.to_json())

# convert the object into a dict
create_many_workflow_runs201_response_data_dict = create_many_workflow_runs201_response_data_instance.to_dict()
# create an instance of CreateManyWorkflowRuns201ResponseData from a dict
create_many_workflow_runs201_response_data_from_dict = CreateManyWorkflowRuns201ResponseData.from_dict(create_many_workflow_runs201_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


