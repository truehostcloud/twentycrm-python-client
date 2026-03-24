# BlocklistForUpdate

Blocklist

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**handle** | **str** | Handle | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.blocklist_for_update import BlocklistForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of BlocklistForUpdate from a JSON string
blocklist_for_update_instance = BlocklistForUpdate.from_json(json)
# print the JSON string representation of the object
print(BlocklistForUpdate.to_json())

# convert the object into a dict
blocklist_for_update_dict = blocklist_for_update_instance.to_dict()
# create an instance of BlocklistForUpdate from a dict
blocklist_for_update_from_dict = BlocklistForUpdate.from_dict(blocklist_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


