# CalendarChannelEventAssociationForUpdate

Calendar Channel Event Associations

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_external_id** | **str** | Event external ID | [optional] 
**recurring_event_external_id** | **str** | Recurring Event ID | [optional] 
**calendar_channel_id** | **UUID** |  | [optional] 
**calendar_event_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_channel_event_association_for_update import CalendarChannelEventAssociationForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelEventAssociationForUpdate from a JSON string
calendar_channel_event_association_for_update_instance = CalendarChannelEventAssociationForUpdate.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelEventAssociationForUpdate.to_json())

# convert the object into a dict
calendar_channel_event_association_for_update_dict = calendar_channel_event_association_for_update_instance.to_dict()
# create an instance of CalendarChannelEventAssociationForUpdate from a dict
calendar_channel_event_association_for_update_from_dict = CalendarChannelEventAssociationForUpdate.from_dict(calendar_channel_event_association_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


