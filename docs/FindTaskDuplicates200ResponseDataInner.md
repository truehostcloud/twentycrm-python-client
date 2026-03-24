# FindTaskDuplicates200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **float** |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**task_duplicates** | [**List[TaskForResponse]**](TaskForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_task_duplicates200_response_data_inner import FindTaskDuplicates200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of FindTaskDuplicates200ResponseDataInner from a JSON string
find_task_duplicates200_response_data_inner_instance = FindTaskDuplicates200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(FindTaskDuplicates200ResponseDataInner.to_json())

# convert the object into a dict
find_task_duplicates200_response_data_inner_dict = find_task_duplicates200_response_data_inner_instance.to_dict()
# create an instance of FindTaskDuplicates200ResponseDataInner from a dict
find_task_duplicates200_response_data_inner_from_dict = FindTaskDuplicates200ResponseDataInner.from_dict(find_task_duplicates200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


