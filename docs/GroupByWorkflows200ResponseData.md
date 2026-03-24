# GroupByWorkflows200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**workflows_group_by** | [**List[GroupByWorkflows200ResponseDataWorkflowsGroupByInner]**](GroupByWorkflows200ResponseDataWorkflowsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_workflows200_response_data import GroupByWorkflows200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByWorkflows200ResponseData from a JSON string
group_by_workflows200_response_data_instance = GroupByWorkflows200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByWorkflows200ResponseData.to_json())

# convert the object into a dict
group_by_workflows200_response_data_dict = group_by_workflows200_response_data_instance.to_dict()
# create an instance of GroupByWorkflows200ResponseData from a dict
group_by_workflows200_response_data_from_dict = GroupByWorkflows200ResponseData.from_dict(group_by_workflows200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


