# CompanyAddress

Address of the company

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_street1** | **str** |  | [optional] 
**address_street2** | **str** |  | [optional] 
**address_city** | **str** |  | [optional] 
**address_postcode** | **str** |  | [optional] 
**address_state** | **str** |  | [optional] 
**address_country** | **str** |  | [optional] 
**address_lat** | **float** |  | [optional] 
**address_lng** | **float** |  | [optional] 

## Example

```python
from twentycrm_client.models.company_address import CompanyAddress

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyAddress from a JSON string
company_address_instance = CompanyAddress.from_json(json)
# print the JSON string representation of the object
print(CompanyAddress.to_json())

# convert the object into a dict
company_address_dict = company_address_instance.to_dict()
# create an instance of CompanyAddress from a dict
company_address_from_dict = CompanyAddress.from_dict(company_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


