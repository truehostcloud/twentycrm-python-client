# GroupByCalendarEvents200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**calendar_events_group_by** | [**List[GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner]**](GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.group_by_calendar_events200_response_data import GroupByCalendarEvents200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByCalendarEvents200ResponseData from a JSON string
group_by_calendar_events200_response_data_instance = GroupByCalendarEvents200ResponseData.from_json(json)
# print the JSON string representation of the object
print(GroupByCalendarEvents200ResponseData.to_json())

# convert the object into a dict
group_by_calendar_events200_response_data_dict = group_by_calendar_events200_response_data_instance.to_dict()
# create an instance of GroupByCalendarEvents200ResponseData from a dict
group_by_calendar_events200_response_data_from_dict = GroupByCalendarEvents200ResponseData.from_dict(group_by_calendar_events200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


