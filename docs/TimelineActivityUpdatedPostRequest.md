# TimelineActivityUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**TimelineActivityCreatedPostRequestObjectMetadata**](TimelineActivityCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**TimelineActivityForResponse**](TimelineActivityForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.timeline_activity_updated_post_request import TimelineActivityUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of TimelineActivityUpdatedPostRequest from a JSON string
timeline_activity_updated_post_request_instance = TimelineActivityUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(TimelineActivityUpdatedPostRequest.to_json())

# convert the object into a dict
timeline_activity_updated_post_request_dict = timeline_activity_updated_post_request_instance.to_dict()
# create an instance of TimelineActivityUpdatedPostRequest from a dict
timeline_activity_updated_post_request_from_dict = TimelineActivityUpdatedPostRequest.from_dict(timeline_activity_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


