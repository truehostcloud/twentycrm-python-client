# GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[WorkflowVersionForResponse]**](WorkflowVersionForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_workflow_versions200_response_data_workflow_versions_group_by_inner import GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner from a JSON string
group_by_workflow_versions200_response_data_workflow_versions_group_by_inner_instance = GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner.to_json())

# convert the object into a dict
group_by_workflow_versions200_response_data_workflow_versions_group_by_inner_dict = group_by_workflow_versions200_response_data_workflow_versions_group_by_inner_instance.to_dict()
# create an instance of GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner from a dict
group_by_workflow_versions200_response_data_workflow_versions_group_by_inner_from_dict = GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner.from_dict(group_by_workflow_versions200_response_data_workflow_versions_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


