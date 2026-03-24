# FindOpportunityDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Opportunity]**](Opportunity.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_opportunity_duplicates_request import FindOpportunityDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindOpportunityDuplicatesRequest from a JSON string
find_opportunity_duplicates_request_instance = FindOpportunityDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindOpportunityDuplicatesRequest.to_json())

# convert the object into a dict
find_opportunity_duplicates_request_dict = find_opportunity_duplicates_request_instance.to_dict()
# create an instance of FindOpportunityDuplicatesRequest from a dict
find_opportunity_duplicates_request_from_dict = FindOpportunityDuplicatesRequest.from_dict(find_opportunity_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


