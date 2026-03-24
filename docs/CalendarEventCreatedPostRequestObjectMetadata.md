# CalendarEventCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_event_created_post_request_object_metadata import CalendarEventCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarEventCreatedPostRequestObjectMetadata from a JSON string
calendar_event_created_post_request_object_metadata_instance = CalendarEventCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(CalendarEventCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
calendar_event_created_post_request_object_metadata_dict = calendar_event_created_post_request_object_metadata_instance.to_dict()
# create an instance of CalendarEventCreatedPostRequestObjectMetadata from a dict
calendar_event_created_post_request_object_metadata_from_dict = CalendarEventCreatedPostRequestObjectMetadata.from_dict(calendar_event_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


