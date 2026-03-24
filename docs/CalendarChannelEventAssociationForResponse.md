# CalendarChannelEventAssociationForResponse

Calendar Channel Event Associations

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**event_external_id** | **str** | Event external ID | [optional] 
**recurring_event_external_id** | **str** | Recurring Event ID | [optional] 
**calendar_channel_id** | **UUID** |  | [optional] 
**calendar_event_id** | **UUID** |  | [optional] 
**calendar_channel** | [**CalendarChannelForResponse**](CalendarChannelForResponse.md) |  | [optional] 
**calendar_event** | [**CalendarEventForResponse**](CalendarEventForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_channel_event_association_for_response import CalendarChannelEventAssociationForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelEventAssociationForResponse from a JSON string
calendar_channel_event_association_for_response_instance = CalendarChannelEventAssociationForResponse.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelEventAssociationForResponse.to_json())

# convert the object into a dict
calendar_channel_event_association_for_response_dict = calendar_channel_event_association_for_response_instance.to_dict()
# create an instance of CalendarChannelEventAssociationForResponse from a dict
calendar_channel_event_association_for_response_from_dict = CalendarChannelEventAssociationForResponse.from_dict(calendar_channel_event_association_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


