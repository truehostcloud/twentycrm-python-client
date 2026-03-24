# GroupByWorkflowVersions200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**workflow_versions_group_by** | [**List[GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner]**](GroupByWorkflowVersions200ResponseDataWorkflowVersionsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_workflow_versions200_response_data import GroupByWorkflowVersions200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByWorkflowVersions200ResponseData from a JSON string
group_by_workflow_versions200_response_data_instance = GroupByWorkflowVersions200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByWorkflowVersions200ResponseData.to_json())

# convert the object into a dict
group_by_workflow_versions200_response_data_dict = group_by_workflow_versions200_response_data_instance.to_dict()
# create an instance of GroupByWorkflowVersions200ResponseData from a dict
group_by_workflow_versions200_response_data_from_dict = GroupByWorkflowVersions200ResponseData.from_dict(group_by_workflow_versions200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


