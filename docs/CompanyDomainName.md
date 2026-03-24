# CompanyDomainName

The company website URL. We use this url to fetch the company icon

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_link_label** | **str** |  | [optional] 
**primary_link_url** | **str** |  | [optional] 
**secondary_links** | [**List[CalendarEventConferenceLinkSecondaryLinksInner]**](CalendarEventConferenceLinkSecondaryLinksInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.company_domain_name import CompanyDomainName

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyDomainName from a JSON string
company_domain_name_instance = CompanyDomainName.from_json(json)
# print the JSON string representation of the object
print(CompanyDomainName.to_json())

# convert the object into a dict
company_domain_name_dict = company_domain_name_instance.to_dict()
# create an instance of CompanyDomainName from a dict
company_domain_name_from_dict = CompanyDomainName.from_dict(company_domain_name_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


