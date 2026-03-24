# RestoreOneCompany200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**restore_company** | [**CompanyForResponse**](CompanyForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.restore_one_company200_response_data import RestoreOneCompany200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of RestoreOneCompany200ResponseData from a JSON string
restore_one_company200_response_data_instance = RestoreOneCompany200ResponseData.from_json(json)
# print the JSON string representation of the object
print(RestoreOneCompany200ResponseData.to_json())

# convert the object into a dict
restore_one_company200_response_data_dict = restore_one_company200_response_data_instance.to_dict()
# create an instance of RestoreOneCompany200ResponseData from a dict
restore_one_company200_response_data_from_dict = RestoreOneCompany200ResponseData.from_dict(restore_one_company200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


