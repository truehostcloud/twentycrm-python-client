# CalendarEventForUpdate

Calendar events

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | Title | [optional] 
**is_canceled** | **bool** | Is canceled | [optional] 
**is_full_day** | **bool** | Is Full Day | [optional] 
**starts_at** | **datetime** | Start Date | [optional] 
**ends_at** | **datetime** | End Date | [optional] 
**external_created_at** | **datetime** | Creation DateTime | [optional] 
**external_updated_at** | **datetime** | Update DateTime | [optional] 
**description** | **str** | Description | [optional] 
**location** | **str** | Location | [optional] 
**i_cal_uid** | **str** | iCal UID | [optional] 
**conference_solution** | **str** | Conference Solution | [optional] 
**conference_link** | [**CalendarEventConferenceLink**](CalendarEventConferenceLink.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_for_update import CalendarEventForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventForUpdate from a JSON string
calendar_event_for_update_instance = CalendarEventForUpdate.from_json(json)
# print the JSON string representation of the object
print(CalendarEventForUpdate.to_json())

# convert the object into a dict
calendar_event_for_update_dict = calendar_event_for_update_instance.to_dict()
# create an instance of CalendarEventForUpdate from a dict
calendar_event_for_update_from_dict = CalendarEventForUpdate.from_dict(calendar_event_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


