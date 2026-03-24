# GroupByPeople200ResponseDataPeopleGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[PersonForResponse]**](PersonForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_people200_response_data_people_group_by_inner import GroupByPeople200ResponseDataPeopleGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByPeople200ResponseDataPeopleGroupByInner from a JSON string
group_by_people200_response_data_people_group_by_inner_instance = GroupByPeople200ResponseDataPeopleGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByPeople200ResponseDataPeopleGroupByInner.to_json())

# convert the object into a dict
group_by_people200_response_data_people_group_by_inner_dict = group_by_people200_response_data_people_group_by_inner_instance.to_dict()
# create an instance of GroupByPeople200ResponseDataPeopleGroupByInner from a dict
group_by_people200_response_data_people_group_by_inner_from_dict = GroupByPeople200ResponseDataPeopleGroupByInner.from_dict(group_by_people200_response_data_people_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


