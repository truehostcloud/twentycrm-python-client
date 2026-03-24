# GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[ConnectedAccountForResponse]**](ConnectedAccountForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_connected_accounts200_response_data_connected_accounts_group_by_inner import GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner from a JSON string
group_by_connected_accounts200_response_data_connected_accounts_group_by_inner_instance = GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner.to_json())

# convert the object into a dict
group_by_connected_accounts200_response_data_connected_accounts_group_by_inner_dict = group_by_connected_accounts200_response_data_connected_accounts_group_by_inner_instance.to_dict()
# create an instance of GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner from a dict
group_by_connected_accounts200_response_data_connected_accounts_group_by_inner_from_dict = GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner.from_dict(group_by_connected_accounts200_response_data_connected_accounts_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


