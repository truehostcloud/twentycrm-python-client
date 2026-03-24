# CalendarChannelForResponse

Calendar Channels

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**handle** | **str** | Handle | [optional] 
**visibility** | **str** | Visibility | [optional] 
**is_contact_auto_creation_enabled** | **bool** | Is Contact Auto Creation Enabled | [optional] 
**contact_auto_creation_policy** | **str** | Automatically create records for people you participated with in an event. | [optional] 
**is_sync_enabled** | **bool** | Is Sync Enabled | [optional] 
**sync_cursor** | **str** | Sync Cursor. Used for syncing events from the calendar provider | [optional] 
**sync_status** | **str** | Sync status | [optional] 
**sync_stage** | **str** | Sync stage | [optional] 
**sync_stage_started_at** | **datetime** | Sync stage started at | [optional] 
**synced_at** | **datetime** | Last sync date | [optional] 
**throttle_failure_count** | **int** | Throttle Failure Count | [optional] 
**connected_account_id** | **UUID** |  | [optional] 
**calendar_channel_event_associations** | [**List[CalendarChannelEventAssociationForResponse]**](CalendarChannelEventAssociationForResponse.md) | Calendar Channel Event Associations | [optional] 
**connected_account** | [**ConnectedAccountForResponse**](ConnectedAccountForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.calendar_channel_for_response import CalendarChannelForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of CalendarChannelForResponse from a JSON string
calendar_channel_for_response_instance = CalendarChannelForResponse.from_json(json)
# print the JSON string representation of the object
print(CalendarChannelForResponse.to_json())

# convert the object into a dict
calendar_channel_for_response_dict = calendar_channel_for_response_instance.to_dict()
# create an instance of CalendarChannelForResponse from a dict
calendar_channel_for_response_from_dict = CalendarChannelForResponse.from_dict(calendar_channel_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


