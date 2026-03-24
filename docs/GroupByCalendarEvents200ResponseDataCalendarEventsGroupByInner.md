# GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[CalendarEventForResponse]**](CalendarEventForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_calendar_events200_response_data_calendar_events_group_by_inner import GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner from a JSON string
group_by_calendar_events200_response_data_calendar_events_group_by_inner_instance = GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner.to_json())

# convert the object into a dict
group_by_calendar_events200_response_data_calendar_events_group_by_inner_dict = group_by_calendar_events200_response_data_calendar_events_group_by_inner_instance.to_dict()
# create an instance of GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner from a dict
group_by_calendar_events200_response_data_calendar_events_group_by_inner_from_dict = GroupByCalendarEvents200ResponseDataCalendarEventsGroupByInner.from_dict(group_by_calendar_events200_response_data_calendar_events_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


