# FindTaskDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Task]**](Task.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_task_duplicates_request import FindTaskDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindTaskDuplicatesRequest from a JSON string
find_task_duplicates_request_instance = FindTaskDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindTaskDuplicatesRequest.to_json())

# convert the object into a dict
find_task_duplicates_request_dict = find_task_duplicates_request_instance.to_dict()
# create an instance of FindTaskDuplicatesRequest from a dict
find_task_duplicates_request_from_dict = FindTaskDuplicatesRequest.from_dict(find_task_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


