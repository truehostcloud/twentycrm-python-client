# CalendarEventParticipantCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**CalendarEventParticipantCreatedPostRequestObjectMetadata**](CalendarEventParticipantCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**CalendarEventParticipantForResponse**](CalendarEventParticipantForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_participant_created_post_request import CalendarEventParticipantCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventParticipantCreatedPostRequest from a JSON string
calendar_event_participant_created_post_request_instance = CalendarEventParticipantCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(CalendarEventParticipantCreatedPostRequest.to_json())

# convert the object into a dict
calendar_event_participant_created_post_request_dict = calendar_event_participant_created_post_request_instance.to_dict()
# create an instance of CalendarEventParticipantCreatedPostRequest from a dict
calendar_event_participant_created_post_request_from_dict = CalendarEventParticipantCreatedPostRequest.from_dict(calendar_event_participant_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


