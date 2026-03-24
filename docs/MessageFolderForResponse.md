# MessageFolderForResponse

Message Folders

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | **str** | Folder name | [optional] 
**sync_cursor** | **str** | Sync Cursor | [optional] 
**is_sent_folder** | **bool** | Is Sent Folder | [optional] 
**is_synced** | **bool** | Is Synced | [optional] 
**parent_folder_id** | **str** | Parent Folder ID | [optional] 
**external_id** | **str** | External ID | [optional] 
**pending_sync_action** | **str** | Pending action for folder sync | [optional] 
**message_channel_id** | **UUID** |  | [optional] 
**message_channel** | [**MessageChannelForResponse**](MessageChannelForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.message_folder_for_response import MessageFolderForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of MessageFolderForResponse from a JSON string
message_folder_for_response_instance = MessageFolderForResponse.from_json(json)
# print the JSON string representation of the object
print(MessageFolderForResponse.to_json())

# convert the object into a dict
message_folder_for_response_dict = message_folder_for_response_instance.to_dict()
# create an instance of MessageFolderForResponse from a dict
message_folder_for_response_from_dict = MessageFolderForResponse.from_dict(message_folder_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


