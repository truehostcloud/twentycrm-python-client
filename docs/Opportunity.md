# Opportunity

An opportunity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The opportunity name | [optional] 
**amount** | [**OpportunityAmount**](OpportunityAmount.md) |  | [optional] 
**close_date** | **datetime** | Opportunity close date | [optional] 
**stage** | **str** | Opportunity stage | [optional] 
**position** | **float** | Opportunity record position | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 
**company_id** | **UUID** |  | [optional] 
**point_of_contact_id** | **UUID** |  | [optional] 
**owner_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.opportunity import Opportunity

# TODO update the JSON string below
json = "{}"
# create an instance of Opportunity from a JSON string
opportunity_instance = Opportunity.from_json(json)
# print the JSON string representation of the object
print(Opportunity.to_json())

# convert the object into a dict
opportunity_dict = opportunity_instance.to_dict()
# create an instance of Opportunity from a dict
opportunity_from_dict = Opportunity.from_dict(opportunity_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


