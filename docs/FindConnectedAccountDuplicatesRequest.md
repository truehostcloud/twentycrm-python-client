# FindConnectedAccountDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[ConnectedAccount]**](ConnectedAccount.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_connected_account_duplicates_request import FindConnectedAccountDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindConnectedAccountDuplicatesRequest from a JSON string
find_connected_account_duplicates_request_instance = FindConnectedAccountDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindConnectedAccountDuplicatesRequest.to_json())

# convert the object into a dict
find_connected_account_duplicates_request_dict = find_connected_account_duplicates_request_instance.to_dict()
# create an instance of FindConnectedAccountDuplicatesRequest from a dict
find_connected_account_duplicates_request_from_dict = FindConnectedAccountDuplicatesRequest.from_dict(find_connected_account_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


