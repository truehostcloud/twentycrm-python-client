# GroupByWorkflows200ResponseDataWorkflowsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[WorkflowForResponse]**](WorkflowForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_workflows200_response_data_workflows_group_by_inner import GroupByWorkflows200ResponseDataWorkflowsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByWorkflows200ResponseDataWorkflowsGroupByInner from a JSON string
group_by_workflows200_response_data_workflows_group_by_inner_instance = GroupByWorkflows200ResponseDataWorkflowsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByWorkflows200ResponseDataWorkflowsGroupByInner.to_json())

# convert the object into a dict
group_by_workflows200_response_data_workflows_group_by_inner_dict = group_by_workflows200_response_data_workflows_group_by_inner_instance.to_dict()
# create an instance of GroupByWorkflows200ResponseDataWorkflowsGroupByInner from a dict
group_by_workflows200_response_data_workflows_group_by_inner_from_dict = GroupByWorkflows200ResponseDataWorkflowsGroupByInner.from_dict(group_by_workflows200_response_data_workflows_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


