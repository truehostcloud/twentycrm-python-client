# FindBlocklistDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Blocklist]**](Blocklist.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_blocklist_duplicates_request import FindBlocklistDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindBlocklistDuplicatesRequest from a JSON string
find_blocklist_duplicates_request_instance = FindBlocklistDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindBlocklistDuplicatesRequest.to_json())

# convert the object into a dict
find_blocklist_duplicates_request_dict = find_blocklist_duplicates_request_instance.to_dict()
# create an instance of FindBlocklistDuplicatesRequest from a dict
find_blocklist_duplicates_request_from_dict = FindBlocklistDuplicatesRequest.from_dict(find_blocklist_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


