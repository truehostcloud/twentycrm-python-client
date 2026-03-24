# GroupByOpportunities200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**opportunities_group_by** | [**List[GroupByOpportunities200ResponseDataOpportunitiesGroupByInner]**](GroupByOpportunities200ResponseDataOpportunitiesGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_opportunities200_response_data import GroupByOpportunities200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByOpportunities200ResponseData from a JSON string
group_by_opportunities200_response_data_instance = GroupByOpportunities200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByOpportunities200ResponseData.to_json())

# convert the object into a dict
group_by_opportunities200_response_data_dict = group_by_opportunities200_response_data_instance.to_dict()
# create an instance of GroupByOpportunities200ResponseData from a dict
group_by_opportunities200_response_data_from_dict = GroupByOpportunities200ResponseData.from_dict(group_by_opportunities200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


