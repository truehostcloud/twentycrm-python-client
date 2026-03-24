# FindTimelineActivityDuplicates200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **float** |  | [optional] 
**page_info** | [**FindManyAttachments200ResponsePageInfo**](FindManyAttachments200ResponsePageInfo.md) |  | [optional] 
**timeline_activity_duplicates** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_timeline_activity_duplicates200_response_data_inner import FindTimelineActivityDuplicates200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of FindTimelineActivityDuplicates200ResponseDataInner from a JSON string
find_timeline_activity_duplicates200_response_data_inner_instance = FindTimelineActivityDuplicates200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(FindTimelineActivityDuplicates200ResponseDataInner.to_json())

# convert the object into a dict
find_timeline_activity_duplicates200_response_data_inner_dict = find_timeline_activity_duplicates200_response_data_inner_instance.to_dict()
# create an instance of FindTimelineActivityDuplicates200ResponseDataInner from a dict
find_timeline_activity_duplicates200_response_data_inner_from_dict = FindTimelineActivityDuplicates200ResponseDataInner.from_dict(find_timeline_activity_duplicates200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


