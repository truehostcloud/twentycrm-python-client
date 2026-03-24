# CompanyLinkedinLink

The company Linkedin account

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_link_label** | **str** |  | [optional] 
**primary_link_url** | **str** |  | [optional] 
**secondary_links** | [**List[CalendarEventConferenceLinkSecondaryLinksInner]**](CalendarEventConferenceLinkSecondaryLinksInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.company_linkedin_link import CompanyLinkedinLink

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyLinkedinLink from a JSON string
company_linkedin_link_instance = CompanyLinkedinLink.from_json(json)
# print the JSON string representation of the object
print(CompanyLinkedinLink.to_json())

# convert the object into a dict
company_linkedin_link_dict = company_linkedin_link_instance.to_dict()
# create an instance of CompanyLinkedinLink from a dict
company_linkedin_link_from_dict = CompanyLinkedinLink.from_dict(company_linkedin_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


