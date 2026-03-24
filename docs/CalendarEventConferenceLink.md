# CalendarEventConferenceLink

Meet Link

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**primary_link_label** | **str** |  | [optional] 
**primary_link_url** | **str** |  | [optional] 
**secondary_links** | [**List[CalendarEventConferenceLinkSecondaryLinksInner]**](CalendarEventConferenceLinkSecondaryLinksInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_conference_link import CalendarEventConferenceLink

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventConferenceLink from a JSON string
calendar_event_conference_link_instance = CalendarEventConferenceLink.from_json(json)
# print the JSON string representation of the object
print(CalendarEventConferenceLink.to_json())

# convert the object into a dict
calendar_event_conference_link_dict = calendar_event_conference_link_instance.to_dict()
# create an instance of CalendarEventConferenceLink from a dict
calendar_event_conference_link_from_dict = CalendarEventConferenceLink.from_dict(calendar_event_conference_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


