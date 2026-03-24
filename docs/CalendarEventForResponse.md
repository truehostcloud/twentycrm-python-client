# CalendarEventForResponse

Calendar events

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | Title | [optional] 
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
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
**calendar_channel_event_associations** | [**List[CalendarChannelEventAssociationForResponse]**](CalendarChannelEventAssociationForResponse.md) | Calendar Channel Event Associations | [optional] 
**calendar_event_participants** | [**List[CalendarEventParticipantForResponse]**](CalendarEventParticipantForResponse.md) | Event Participants | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_for_response import CalendarEventForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventForResponse from a JSON string
calendar_event_for_response_instance = CalendarEventForResponse.from_json(json)
# print the JSON string representation of the object
print(CalendarEventForResponse.to_json())

# convert the object into a dict
calendar_event_for_response_dict = calendar_event_for_response_instance.to_dict()
# create an instance of CalendarEventForResponse from a dict
calendar_event_for_response_from_dict = CalendarEventForResponse.from_dict(calendar_event_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


