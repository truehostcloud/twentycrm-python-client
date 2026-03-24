# GroupByBlocklists200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**blocklists_group_by** | [**List[GroupByBlocklists200ResponseDataBlocklistsGroupByInner]**](GroupByBlocklists200ResponseDataBlocklistsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_blocklists200_response_data import GroupByBlocklists200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByBlocklists200ResponseData from a JSON string
group_by_blocklists200_response_data_instance = GroupByBlocklists200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByBlocklists200ResponseData.to_json())

# convert the object into a dict
group_by_blocklists200_response_data_dict = group_by_blocklists200_response_data_instance.to_dict()
# create an instance of GroupByBlocklists200ResponseData from a dict
group_by_blocklists200_response_data_from_dict = GroupByBlocklists200ResponseData.from_dict(group_by_blocklists200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


