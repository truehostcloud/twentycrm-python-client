# FindTaskTargetDuplicates200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[FindTaskTargetDuplicates200ResponseDataInner]**](FindTaskTargetDuplicates200ResponseDataInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_task_target_duplicates200_response import FindTaskTargetDuplicates200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindTaskTargetDuplicates200Response from a JSON string
find_task_target_duplicates200_response_instance = FindTaskTargetDuplicates200Response.from_json(json)
# print the JSON string representation of the object
print(FindTaskTargetDuplicates200Response.to_json())

# convert the object into a dict
find_task_target_duplicates200_response_dict = find_task_target_duplicates200_response_instance.to_dict()
# create an instance of FindTaskTargetDuplicates200Response from a dict
find_task_target_duplicates200_response_from_dict = FindTaskTargetDuplicates200Response.from_dict(find_task_target_duplicates200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


