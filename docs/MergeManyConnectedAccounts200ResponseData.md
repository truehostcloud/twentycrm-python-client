# MergeManyConnectedAccounts200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**merge_connected_accounts** | [**ConnectedAccountForResponse**](ConnectedAccountForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.merge_many_connected_accounts200_response_data import MergeManyConnectedAccounts200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of MergeManyConnectedAccounts200ResponseData from a JSON string
merge_many_connected_accounts200_response_data_instance = MergeManyConnectedAccounts200ResponseData.from_json(json)
# print the JSON string representation of the object
print(MergeManyConnectedAccounts200ResponseData.to_json())

# convert the object into a dict
merge_many_connected_accounts200_response_data_dict = merge_many_connected_accounts200_response_data_instance.to_dict()
# create an instance of MergeManyConnectedAccounts200ResponseData from a dict
merge_many_connected_accounts200_response_data_from_dict = MergeManyConnectedAccounts200ResponseData.from_dict(merge_many_connected_accounts200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


