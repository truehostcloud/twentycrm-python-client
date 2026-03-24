# FindManyOpportunities200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**opportunities** | [**List[OpportunityForResponse]**](OpportunityForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_opportunities200_response_data import FindManyOpportunities200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyOpportunities200ResponseData from a JSON string
find_many_opportunities200_response_data_instance = FindManyOpportunities200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindManyOpportunities200ResponseData.to_json())

# convert the object into a dict
find_many_opportunities200_response_data_dict = find_many_opportunities200_response_data_instance.to_dict()
# create an instance of FindManyOpportunities200ResponseData from a dict
find_many_opportunities200_response_data_from_dict = FindManyOpportunities200ResponseData.from_dict(find_many_opportunities200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


