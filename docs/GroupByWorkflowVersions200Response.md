# GroupByWorkflowVersions200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**GroupByWorkflowVersions200ResponseData**](GroupByWorkflowVersions200ResponseData.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_workflow_versions200_response import GroupByWorkflowVersions200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByWorkflowVersions200Response from a JSON string
group_by_workflow_versions200_response_instance = GroupByWorkflowVersions200Response.from_json(json)
# print the JSON string representation of the object
print(GroupByWorkflowVersions200Response.to_json())

# convert the object into a dict
group_by_workflow_versions200_response_dict = group_by_workflow_versions200_response_instance.to_dict()
# create an instance of GroupByWorkflowVersions200Response from a dict
group_by_workflow_versions200_response_from_dict = GroupByWorkflowVersions200Response.from_dict(group_by_workflow_versions200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


