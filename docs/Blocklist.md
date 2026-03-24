# Blocklist

Blocklist

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**handle** | **str** | Handle | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.blocklist import Blocklist

# TODO update the JSON string below
json = "{}"
# create an instance of Blocklist from a JSON string
blocklist_instance = Blocklist.from_json(json)
# print the JSON string representation of the object
print(Blocklist.to_json())

# convert the object into a dict
blocklist_dict = blocklist_instance.to_dict()
# create an instance of Blocklist from a dict
blocklist_from_dict = Blocklist.from_dict(blocklist_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


