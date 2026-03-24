# MessageChannelForResponse

Message Channels

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
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
**connected_account** | [**ConnectedAccountForResponse**](ConnectedAccountForResponse.md) |  | [optional] 
**message_channel_message_associations** | [**List[MessageChannelMessageAssociationForResponse]**](MessageChannelMessageAssociationForResponse.md) | Messages from the channel. | [optional] 
**message_folders** | [**List[MessageFolderForResponse]**](MessageFolderForResponse.md) | Message Folders | [optional] 

## Example

```python
from twentycrm_client.models.message_channel_for_response import MessageChannelForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MessageChannelForResponse from a JSON string
message_channel_for_response_instance = MessageChannelForResponse.from_json(json)
# print the JSON string representation of the object
print(MessageChannelForResponse.to_json())

# convert the object into a dict
message_channel_for_response_dict = message_channel_for_response_instance.to_dict()
# create an instance of MessageChannelForResponse from a dict
message_channel_for_response_from_dict = MessageChannelForResponse.from_dict(message_channel_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


