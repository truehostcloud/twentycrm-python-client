# FindManyTasks200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tasks** | [**List[TaskForResponse]**](TaskForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_tasks200_response_data import FindManyTasks200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyTasks200ResponseData from a JSON string
find_many_tasks200_response_data_instance = FindManyTasks200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindManyTasks200ResponseData.to_json())

# convert the object into a dict
find_many_tasks200_response_data_dict = find_many_tasks200_response_data_instance.to_dict()
# create an instance of FindManyTasks200ResponseData from a dict
find_many_tasks200_response_data_from_dict = FindManyTasks200ResponseData.from_dict(find_many_tasks200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


