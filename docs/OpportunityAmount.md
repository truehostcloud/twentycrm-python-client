# OpportunityAmount

Opportunity amount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount_micros** | **float** |  | [optional] 
**currency_code** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.opportunity_amount import OpportunityAmount

# TODO update the JSON string below
json = "{}"
# create an instance of OpportunityAmount from a JSON string
opportunity_amount_instance = OpportunityAmount.from_json(json)
# print the JSON string representation of the object
print(OpportunityAmount.to_json())

# convert the object into a dict
opportunity_amount_dict = opportunity_amount_instance.to_dict()
# create an instance of OpportunityAmount from a dict
opportunity_amount_from_dict = OpportunityAmount.from_dict(opportunity_amount_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


