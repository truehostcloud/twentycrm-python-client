# GroupByCalendarChannelEventAssociations200ResponseDataCalendarChannelEventAssociationsGroupByInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_by_dimension_values** | **List[str]** | Array of values representing each dimension in the group | [optional] 
**records** | [**List[CalendarChannelEventAssociationForResponse]**](CalendarChannelEventAssociationForResponse.md) | Sample of records for this group (only present when include_records_sample is true) | [optional] 

## Example

```python
from twentycrm_client.models.group_by_calendar_channel_event_associations200_response_data_calendar_channel_event_associations_group_by_inner import GroupByCalendarChannelEventAssociations200ResponseDataCalendarChannelEventAssociationsGroupByInner

# TODO update the JSON string below
json = "{}"
# create an instance of GroupByCalendarChannelEventAssociations200ResponseDataCalendarChannelEventAssociationsGroupByInner from a JSON string
group_by_calendar_channel_event_associations200_response_data_calendar_channel_event_associations_group_by_inner_instance = GroupByCalendarChannelEventAssociations200ResponseDataCalendarChannelEventAssociationsGroupByInner.from_json(json)
# print the JSON string representation of the object
print(GroupByCalendarChannelEventAssociations200ResponseDataCalendarChannelEventAssociationsGroupByInner.to_json())

# convert the object into a dict
group_by_calendar_channel_event_associations200_response_data_calendar_channel_event_associations_group_by_inner_dict = group_by_calendar_channel_event_associations200_response_data_calendar_channel_event_associations_group_by_inner_instance.to_dict()
# create an instance of GroupByCalendarChannelEventAssociations200ResponseDataCalendarChannelEventAssociationsGroupByInner from a dict
group_by_calendar_channel_event_associations200_response_data_calendar_channel_event_associations_group_by_inner_from_dict = GroupByCalendarChannelEventAssociations200ResponseDataCalendarChannelEventAssociationsGroupByInner.from_dict(group_by_calendar_channel_event_associations200_response_data_calendar_channel_event_associations_group_by_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


