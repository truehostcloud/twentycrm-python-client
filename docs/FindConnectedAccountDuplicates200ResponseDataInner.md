# FindConnectedAccountDuplicates200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **float** |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**connected_account_duplicates** | [**List[ConnectedAccountForResponse]**](ConnectedAccountForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_connected_account_duplicates200_response_data_inner import FindConnectedAccountDuplicates200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of FindConnectedAccountDuplicates200ResponseDataInner from a JSON string
find_connected_account_duplicates200_response_data_inner_instance = FindConnectedAccountDuplicates200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(FindConnectedAccountDuplicates200ResponseDataInner.to_json())

# convert the object into a dict
find_connected_account_duplicates200_response_data_inner_dict = find_connected_account_duplicates200_response_data_inner_instance.to_dict()
# create an instance of FindConnectedAccountDuplicates200ResponseDataInner from a dict
find_connected_account_duplicates200_response_data_inner_from_dict = FindConnectedAccountDuplicates200ResponseDataInner.from_dict(find_connected_account_duplicates200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


