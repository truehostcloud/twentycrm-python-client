# OpportunityForResponse

An opportunity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | **str** | The opportunity name | [optional] 
**amount** | [**OpportunityAmount**](OpportunityAmount.md) |  | [optional] 
**close_date** | **datetime** | Opportunity close date | [optional] 
**stage** | **str** | Opportunity stage | [optional] 
**position** | **float** | Opportunity record position | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**company_id** | **UUID** |  | [optional] 
**point_of_contact_id** | **UUID** |  | [optional] 
**owner_id** | **UUID** |  | [optional] 
**attachments** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Attachments linked to the opportunity | [optional] 
**company** | [**CompanyForResponse**](CompanyForResponse.md) |  | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the opportunity | [optional] 
**note_targets** | [**List[NoteTargetForResponse]**](NoteTargetForResponse.md) | Notes tied to the opportunity | [optional] 
**point_of_contact** | [**PersonForResponse**](PersonForResponse.md) |  | [optional] 
**task_targets** | [**List[TaskTargetForResponse]**](TaskTargetForResponse.md) | Tasks tied to the opportunity | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline Activities linked to the opportunity. | [optional] 
**owner** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.opportunity_for_response import OpportunityForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of OpportunityForResponse from a JSON string
opportunity_for_response_instance = OpportunityForResponse.from_json(json)
# print the JSON string representation of the object
print(OpportunityForResponse.to_json())

# convert the object into a dict
opportunity_for_response_dict = opportunity_for_response_instance.to_dict()
# create an instance of OpportunityForResponse from a dict
opportunity_for_response_from_dict = OpportunityForResponse.from_dict(opportunity_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


