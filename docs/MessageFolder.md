# MessageFolder

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
from twentycrm_client.models.message_folder import MessageFolder

# TODO update the JSON string below
json = "{}"
# create an instance of MessageFolder from a JSON string
message_folder_instance = MessageFolder.from_json(json)
# print the JSON string representation of the object
print(MessageFolder.to_json())

# convert the object into a dict
message_folder_dict = message_folder_instance.to_dict()
# create an instance of MessageFolder from a dict
message_folder_from_dict = MessageFolder.from_dict(message_folder_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


