# GroupByConnectedAccounts200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**connected_accounts_group_by** | [**List[GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner]**](GroupByConnectedAccounts200ResponseDataConnectedAccountsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_connected_accounts200_response_data import GroupByConnectedAccounts200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByConnectedAccounts200ResponseData from a JSON string
group_by_connected_accounts200_response_data_instance = GroupByConnectedAccounts200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByConnectedAccounts200ResponseData.to_json())

# convert the object into a dict
group_by_connected_accounts200_response_data_dict = group_by_connected_accounts200_response_data_instance.to_dict()
# create an instance of GroupByConnectedAccounts200ResponseData from a dict
group_by_connected_accounts200_response_data_from_dict = GroupByConnectedAccounts200ResponseData.from_dict(group_by_connected_accounts200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


