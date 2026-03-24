# UpdateManyConnectedAccounts200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**update_connected_accounts** | [**List[ConnectedAccountForResponse]**](ConnectedAccountForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.update_many_connected_accounts200_response_data import UpdateManyConnectedAccounts200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateManyConnectedAccounts200ResponseData from a JSON string
update_many_connected_accounts200_response_data_instance = UpdateManyConnectedAccounts200ResponseData.from_json(json)
# print the JSON string representation of the object
print(UpdateManyConnectedAccounts200ResponseData.to_json())

# convert the object into a dict
update_many_connected_accounts200_response_data_dict = update_many_connected_accounts200_response_data_instance.to_dict()
# create an instance of UpdateManyConnectedAccounts200ResponseData from a dict
update_many_connected_accounts200_response_data_from_dict = UpdateManyConnectedAccounts200ResponseData.from_dict(update_many_connected_accounts200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


