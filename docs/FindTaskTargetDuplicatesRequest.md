# FindTaskTargetDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[TaskTarget]**](TaskTarget.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_task_target_duplicates_request import FindTaskTargetDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindTaskTargetDuplicatesRequest from a JSON string
find_task_target_duplicates_request_instance = FindTaskTargetDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindTaskTargetDuplicatesRequest.to_json())

# convert the object into a dict
find_task_target_duplicates_request_dict = find_task_target_duplicates_request_instance.to_dict()
# create an instance of FindTaskTargetDuplicatesRequest from a dict
find_task_target_duplicates_request_from_dict = FindTaskTargetDuplicatesRequest.from_dict(find_task_target_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


