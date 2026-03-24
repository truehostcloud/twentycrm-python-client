# Company

A company

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The company name | [optional] 
**domain_name** | [**CompanyDomainName**](CompanyDomainName.md) |  | [optional] 
**address** | [**CompanyAddress**](CompanyAddress.md) |  | [optional] 
**employees** | **int** | Number of employees in the company | [optional] 
**linkedin_link** | [**CompanyLinkedinLink**](CompanyLinkedinLink.md) |  | [optional] 
**x_link** | [**CompanyXLink**](CompanyXLink.md) |  | [optional] 
**annual_recurring_revenue** | [**CompanyAnnualRecurringRevenue**](CompanyAnnualRecurringRevenue.md) |  | [optional] 
**ideal_customer_profile** | **bool** | Ideal Customer Profile: Indicates whether the company is the most suitable and valuable customer for you | [optional] 
**position** | **float** | Company record position | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 
**account_owner_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.company import Company

# TODO update the JSON string below
json = "{}"
# create an instance of Company from a JSON string
company_instance = Company.from_json(json)
# print the JSON string representation of the object
print(Company.to_json())

# convert the object into a dict
company_dict = company_instance.to_dict()
# create an instance of Company from a dict
company_from_dict = Company.from_dict(company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


