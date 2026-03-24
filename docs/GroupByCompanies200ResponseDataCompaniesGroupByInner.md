# GroupByCompanies200ResponseDataCompaniesGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[CompanyForResponse]**](CompanyForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_companies200_response_data_companies_group_by_inner import GroupByCompanies200ResponseDataCompaniesGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByCompanies200ResponseDataCompaniesGroupByInner from a JSON string
group_by_companies200_response_data_companies_group_by_inner_instance = GroupByCompanies200ResponseDataCompaniesGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByCompanies200ResponseDataCompaniesGroupByInner.to_json())

# convert the object into a dict
group_by_companies200_response_data_companies_group_by_inner_dict = group_by_companies200_response_data_companies_group_by_inner_instance.to_dict()
# create an instance of GroupByCompanies200ResponseDataCompaniesGroupByInner from a dict
group_by_companies200_response_data_companies_group_by_inner_from_dict = GroupByCompanies200ResponseDataCompaniesGroupByInner.from_dict(group_by_companies200_response_data_companies_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


