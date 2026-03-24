# FindCompanyDuplicates200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **float** |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**company_duplicates** | [**List[CompanyForResponse]**](CompanyForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_company_duplicates200_response_data_inner import FindCompanyDuplicates200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of FindCompanyDuplicates200ResponseDataInner from a JSON string
find_company_duplicates200_response_data_inner_instance = FindCompanyDuplicates200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(FindCompanyDuplicates200ResponseDataInner.to_json())

# convert the object into a dict
find_company_duplicates200_response_data_inner_dict = find_company_duplicates200_response_data_inner_instance.to_dict()
# create an instance of FindCompanyDuplicates200ResponseDataInner from a dict
find_company_duplicates200_response_data_inner_from_dict = FindCompanyDuplicates200ResponseDataInner.from_dict(find_company_duplicates200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


