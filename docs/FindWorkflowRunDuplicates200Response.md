# FindWorkflowRunDuplicates200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[FindWorkflowRunDuplicates200ResponseDataInner]**](FindWorkflowRunDuplicates200ResponseDataInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_workflow_run_duplicates200_response import FindWorkflowRunDuplicates200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindWorkflowRunDuplicates200Response from a JSON string
find_workflow_run_duplicates200_response_instance = FindWorkflowRunDuplicates200Response.from_json(json)
# print the JSON string representation of the object
print(FindWorkflowRunDuplicates200Response.to_json())

# convert the object into a dict
find_workflow_run_duplicates200_response_dict = find_workflow_run_duplicates200_response_instance.to_dict()
# create an instance of FindWorkflowRunDuplicates200Response from a dict
find_workflow_run_duplicates200_response_from_dict = FindWorkflowRunDuplicates200Response.from_dict(find_workflow_run_duplicates200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


