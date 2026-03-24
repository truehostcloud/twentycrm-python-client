# BlocklistForResponse

Blocklist

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**handle** | **str** | Handle | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 
**workspace_member** | [**WorkspaceMemberForResponse**](WorkspaceMemberForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.blocklist_for_response import BlocklistForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of BlocklistForResponse from a JSON string
blocklist_for_response_instance = BlocklistForResponse.from_json(json)
# print the JSON string representation of the object
print(BlocklistForResponse.to_json())

# convert the object into a dict
blocklist_for_response_dict = blocklist_for_response_instance.to_dict()
# create an instance of BlocklistForResponse from a dict
blocklist_for_response_from_dict = BlocklistForResponse.from_dict(blocklist_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


