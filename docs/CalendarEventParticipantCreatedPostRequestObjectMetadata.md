# CalendarEventParticipantCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_participant_created_post_request_object_metadata import CalendarEventParticipantCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventParticipantCreatedPostRequestObjectMetadata from a JSON string
calendar_event_participant_created_post_request_object_metadata_instance = CalendarEventParticipantCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(CalendarEventParticipantCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
calendar_event_participant_created_post_request_object_metadata_dict = calendar_event_participant_created_post_request_object_metadata_instance.to_dict()
# create an instance of CalendarEventParticipantCreatedPostRequestObjectMetadata from a dict
calendar_event_participant_created_post_request_object_metadata_from_dict = CalendarEventParticipantCreatedPostRequestObjectMetadata.from_dict(calendar_event_participant_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


