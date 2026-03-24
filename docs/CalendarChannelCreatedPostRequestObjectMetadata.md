# CalendarChannelCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_channel_created_post_request_object_metadata import CalendarChannelCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelCreatedPostRequestObjectMetadata from a JSON string
calendar_channel_created_post_request_object_metadata_instance = CalendarChannelCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
calendar_channel_created_post_request_object_metadata_dict = calendar_channel_created_post_request_object_metadata_instance.to_dict()
# create an instance of CalendarChannelCreatedPostRequestObjectMetadata from a dict
calendar_channel_created_post_request_object_metadata_from_dict = CalendarChannelCreatedPostRequestObjectMetadata.from_dict(calendar_channel_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


