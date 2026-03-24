# CompanyForResponse

A company

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | **str** | The company name | [optional] 
**domain_name** | [**CompanyDomainName**](CompanyDomainName.md) |  | [optional] 
**address** | [**CompanyAddress**](CompanyAddress.md) |  | [optional] 
**employees** | **int** | Number of employees in the company | [optional] 
**linkedin_link** | [**CompanyLinkedinLink**](CompanyLinkedinLink.md) |  | [optional] 
**x_link** | [**CompanyXLink**](CompanyXLink.md) |  | [optional] 
**annual_recurring_revenue** | [**CompanyAnnualRecurringRevenue**](CompanyAnnualRecurringRevenue.md) |  | [optional] 
**ideal_customer_profile** | **bool** | Ideal Customer Profile: Indicates whether the company is the most suitable and valuable customer for you | [optional] 
**position** | **float** | Company record position | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**account_owner_id** | **UUID** |  | [optional] 
**attachments** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Attachments linked to the company | [optional] 
**people** | [**List[PersonForResponse]**](PersonForResponse.md) | People linked to the company. | [optional] 
**account_owner** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 
**task_targets** | [**List[TaskTargetForResponse]**](TaskTargetForResponse.md) | Tasks tied to the company | [optional] 
**note_targets** | [**List[NoteTargetForResponse]**](NoteTargetForResponse.md) | Notes tied to the company | [optional] 
**opportunities** | [**List[OpportunityForResponse]**](OpportunityForResponse.md) | Opportunities linked to the company. | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the company | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline Activities linked to the company | [optional] 

## Example

```python
from twentycrm_client.models.company_for_response import CompanyForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of CompanyForResponse from a JSON string
company_for_response_instance = CompanyForResponse.from_json(json)
# print the JSON string representation of the object
print(CompanyForResponse.to_json())

# convert the object into a dict
company_for_response_dict = company_for_response_instance.to_dict()
# create an instance of CompanyForResponse from a dict
company_for_response_from_dict = CompanyForResponse.from_dict(company_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


