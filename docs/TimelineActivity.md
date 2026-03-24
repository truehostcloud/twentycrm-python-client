# TimelineActivity

Aggregated / filtered event to be displayed on the timeline

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**happens_at** | **datetime** | Creation date | [optional] 
**name** | **str** | Event name | [optional] 
**properties** | **object** | Json value for event details | [optional] 
**linked_record_cached_name** | **str** | Cached record name | [optional] 
**linked_record_id** | **UUID** | Linked Record id | [optional] 
**linked_object_metadata_id** | **UUID** | Linked Object Metadata Id | [optional] 
**target_company** | **str** | Event target | [optional] 
**target_dashboard** | **str** | Event target | [optional] 
**target_note** | **str** | Event target | [optional] 
**target_opportunity** | **str** | Event target | [optional] 
**target_person** | **str** | Event target | [optional] 
**target_task** | **str** | Event target | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 
**target_workflow** | **str** | Event target | [optional] 
**target_workflow_version** | **str** | Event target | [optional] 
**target_workflow_run** | **str** | Event target | [optional] 

## Example

```python
from twentycrm_client.models.timeline_activity import TimelineActivity

# TODO update the JSON string below
json = "{}"
# create an instance of TimelineActivity from a JSON string
timeline_activity_instance = TimelineActivity.from_json(json)
# print the JSON string representation of the object
print(TimelineActivity.to_json())

# convert the object into a dict
timeline_activity_dict = timeline_activity_instance.to_dict()
# create an instance of TimelineActivity from a dict
timeline_activity_from_dict = TimelineActivity.from_dict(timeline_activity_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


