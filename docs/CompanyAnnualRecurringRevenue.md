# CompanyAnnualRecurringRevenue

Annual Recurring Revenue: The actual or estimated annual revenue of the company

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount_micros** | **float** |  | [optional] 
**currency_code** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.company_annual_recurring_revenue import CompanyAnnualRecurringRevenue

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyAnnualRecurringRevenue from a JSON string
company_annual_recurring_revenue_instance = CompanyAnnualRecurringRevenue.from_json(json)
# print the JSON string representation of the object
print(CompanyAnnualRecurringRevenue.to_json())

# convert the object into a dict
company_annual_recurring_revenue_dict = company_annual_recurring_revenue_instance.to_dict()
# create an instance of CompanyAnnualRecurringRevenue from a dict
company_annual_recurring_revenue_from_dict = CompanyAnnualRecurringRevenue.from_dict(company_annual_recurring_revenue_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


