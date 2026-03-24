# DeleteManyTimelineActivities200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delete_timeline_activities** | [**List[DeleteManyAttachments200ResponseDataDeleteAttachmentsInner]**](DeleteManyAttachments200ResponseDataDeleteAttachmentsInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_timeline_activities200_response_data import DeleteManyTimelineActivities200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyTimelineActivities200ResponseData from a JSON string
delete_many_timeline_activities200_response_data_instance = DeleteManyTimelineActivities200ResponseData.from_json(json)
# print the JSON string representation of the object
print(DeleteManyTimelineActivities200ResponseData.to_json())

# convert the object into a dict
delete_many_timeline_activities200_response_data_dict = delete_many_timeline_activities200_response_data_instance.to_dict()
# create an instance of DeleteManyTimelineActivities200ResponseData from a dict
delete_many_timeline_activities200_response_data_from_dict = DeleteManyTimelineActivities200ResponseData.from_dict(delete_many_timeline_activities200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


