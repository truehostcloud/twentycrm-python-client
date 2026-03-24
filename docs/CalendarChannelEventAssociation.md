# CalendarChannelEventAssociation

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
from twentycrm_client.models.calendar_channel_event_association import CalendarChannelEventAssociation

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelEventAssociation from a JSON string
calendar_channel_event_association_instance = CalendarChannelEventAssociation.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelEventAssociation.to_json())

# convert the object into a dict
calendar_channel_event_association_dict = calendar_channel_event_association_instance.to_dict()
# create an instance of CalendarChannelEventAssociation from a dict
calendar_channel_event_association_from_dict = CalendarChannelEventAssociation.from_dict(calendar_channel_event_association_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


