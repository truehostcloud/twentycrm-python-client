# RestoreOneBlocklist200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**restore_blocklist** | [**BlocklistForResponse**](BlocklistForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_one_blocklist200_response_data import RestoreOneBlocklist200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreOneBlocklist200ResponseData from a JSON string
restore_one_blocklist200_response_data_instance = RestoreOneBlocklist200ResponseData.from_json(json)
# print the JSON string representation of the object
print(RestoreOneBlocklist200ResponseData.to_json())

# convert the object into a dict
restore_one_blocklist200_response_data_dict = restore_one_blocklist200_response_data_instance.to_dict()
# create an instance of RestoreOneBlocklist200ResponseData from a dict
restore_one_blocklist200_response_data_from_dict = RestoreOneBlocklist200ResponseData.from_dict(restore_one_blocklist200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


