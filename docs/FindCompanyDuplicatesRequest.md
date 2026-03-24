# FindCompanyDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Company]**](Company.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_company_duplicates_request import FindCompanyDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindCompanyDuplicatesRequest from a JSON string
find_company_duplicates_request_instance = FindCompanyDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindCompanyDuplicatesRequest.to_json())

# convert the object into a dict
find_company_duplicates_request_dict = find_company_duplicates_request_instance.to_dict()
# create an instance of FindCompanyDuplicatesRequest from a dict
find_company_duplicates_request_from_dict = FindCompanyDuplicatesRequest.from_dict(find_company_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


