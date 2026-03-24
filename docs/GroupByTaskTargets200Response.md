# GroupByTaskTargets200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**GroupByTaskTargets200ResponseData**](GroupByTaskTargets200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_task_targets200_response import GroupByTaskTargets200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByTaskTargets200Response from a JSON string
group_by_task_targets200_response_instance = GroupByTaskTargets200Response.from_json(json)
# print the JSON string representation of the object
print(GroupByTaskTargets200Response.to_json())

# convert the object into a dict
group_by_task_targets200_response_dict = group_by_task_targets200_response_instance.to_dict()
# create an instance of GroupByTaskTargets200Response from a dict
group_by_task_targets200_response_from_dict = GroupByTaskTargets200Response.from_dict(group_by_task_targets200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


