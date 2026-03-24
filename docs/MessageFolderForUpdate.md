# MessageFolderForUpdate

Message Folders

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Folder name | [optional] 
**sync_cursor** | **str** | Sync Cursor | [optional] 
**is_sent_folder** | **bool** | Is Sent Folder | [optional] 
**is_synced** | **bool** | Is Synced | [optional] 
**parent_folder_id** | **str** | Parent Folder ID | [optional] 
**external_id** | **str** | External ID | [optional] 
**pending_sync_action** | **str** | Pending action for folder sync | [optional] 
**message_channel_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_folder_for_update import MessageFolderForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of MessageFolderForUpdate from a JSON string
message_folder_for_update_instance = MessageFolderForUpdate.from_json(json)
# print the JSON string representation of the object
print(MessageFolderForUpdate.to_json())

# convert the object into a dict
message_folder_for_update_dict = message_folder_for_update_instance.to_dict()
# create an instance of MessageFolderForUpdate from a dict
message_folder_for_update_from_dict = MessageFolderForUpdate.from_dict(message_folder_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


