# FindTimelineActivityDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[TimelineActivity]**](TimelineActivity.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_timeline_activity_duplicates_request import FindTimelineActivityDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindTimelineActivityDuplicatesRequest from a JSON string
find_timeline_activity_duplicates_request_instance = FindTimelineActivityDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindTimelineActivityDuplicatesRequest.to_json())

# convert the object into a dict
find_timeline_activity_duplicates_request_dict = find_timeline_activity_duplicates_request_instance.to_dict()
# create an instance of FindTimelineActivityDuplicatesRequest from a dict
find_timeline_activity_duplicates_request_from_dict = FindTimelineActivityDuplicatesRequest.from_dict(find_timeline_activity_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


