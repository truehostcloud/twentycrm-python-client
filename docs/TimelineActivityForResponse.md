# TimelineActivityForResponse

Aggregated / filtered event to be displayed on the timeline

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
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
**workspace_member** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.timeline_activity_for_response import TimelineActivityForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of TimelineActivityForResponse from a JSON string
timeline_activity_for_response_instance = TimelineActivityForResponse.from_json(json)
# print the JSON string representation of the object
print(TimelineActivityForResponse.to_json())

# convert the object into a dict
timeline_activity_for_response_dict = timeline_activity_for_response_instance.to_dict()
# create an instance of TimelineActivityForResponse from a dict
timeline_activity_for_response_from_dict = TimelineActivityForResponse.from_dict(timeline_activity_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


