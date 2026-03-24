# FindManyCompanies200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**companies** | [**List[CompanyForResponse]**](CompanyForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_companies200_response_data import FindManyCompanies200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyCompanies200ResponseData from a JSON string
find_many_companies200_response_data_instance = FindManyCompanies200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindManyCompanies200ResponseData.to_json())

# convert the object into a dict
find_many_companies200_response_data_dict = find_many_companies200_response_data_instance.to_dict()
# create an instance of FindManyCompanies200ResponseData from a dict
find_many_companies200_response_data_from_dict = FindManyCompanies200ResponseData.from_dict(find_many_companies200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


