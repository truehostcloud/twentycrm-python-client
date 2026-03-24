# MessageChannel

Message Channels

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**visibility** | **str** | Visibility | [optional] 
**handle** | **str** | Handle | [optional] 
**type** | **str** | Channel Type | [optional] 
**is_contact_auto_creation_enabled** | **bool** | Is Contact Auto Creation Enabled | [optional] 
**contact_auto_creation_policy** | **str** | Automatically create People records when receiving or sending emails | [optional] 
**message_folder_import_policy** | **str** | Message folder import policy | [optional] 
**exclude_non_professional_emails** | **bool** | Exclude non professional emails | [optional] 
**exclude_group_emails** | **bool** | Exclude group emails | [optional] 
**pending_group_emails_action** | **str** | Pending action for group emails | [optional] 
**is_sync_enabled** | **bool** | Is Sync Enabled | [optional] 
**sync_cursor** | **str** | Last sync cursor | [optional] 
**synced_at** | **datetime** | Last sync date | [optional] 
**sync_status** | **str** | Sync status | [optional] 
**sync_stage** | **str** | Sync stage | [optional] 
**sync_stage_started_at** | **datetime** | Sync stage started at | [optional] 
**throttle_failure_count** | **int** | Throttle Failure Count | [optional] 
**throttle_retry_after** | **datetime** | Throttle Retry After | [optional] 
**connected_account_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_channel import MessageChannel

# TODO update the JSON string below
json = "{}"
# create an instance of MessageChannel from a JSON string
message_channel_instance = MessageChannel.from_json(json)
# print the JSON string representation of the object
print(MessageChannel.to_json())

# convert the object into a dict
message_channel_dict = message_channel_instance.to_dict()
# create an instance of MessageChannel from a dict
message_channel_from_dict = MessageChannel.from_dict(message_channel_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


