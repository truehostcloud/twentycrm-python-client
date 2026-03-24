# GroupByBlocklists200ResponseDataBlocklistsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[BlocklistForResponse]**](BlocklistForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_blocklists200_response_data_blocklists_group_by_inner import GroupByBlocklists200ResponseDataBlocklistsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByBlocklists200ResponseDataBlocklistsGroupByInner from a JSON string
group_by_blocklists200_response_data_blocklists_group_by_inner_instance = GroupByBlocklists200ResponseDataBlocklistsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByBlocklists200ResponseDataBlocklistsGroupByInner.to_json())

# convert the object into a dict
group_by_blocklists200_response_data_blocklists_group_by_inner_dict = group_by_blocklists200_response_data_blocklists_group_by_inner_instance.to_dict()
# create an instance of GroupByBlocklists200ResponseDataBlocklistsGroupByInner from a dict
group_by_blocklists200_response_data_blocklists_group_by_inner_from_dict = GroupByBlocklists200ResponseDataBlocklistsGroupByInner.from_dict(group_by_blocklists200_response_data_blocklists_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


