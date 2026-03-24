# FindMessageFolderDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[MessageFolder]**](MessageFolder.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_message_folder_duplicates_request import FindMessageFolderDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindMessageFolderDuplicatesRequest from a JSON string
find_message_folder_duplicates_request_instance = FindMessageFolderDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindMessageFolderDuplicatesRequest.to_json())

# convert the object into a dict
find_message_folder_duplicates_request_dict = find_message_folder_duplicates_request_instance.to_dict()
# create an instance of FindMessageFolderDuplicatesRequest from a dict
find_message_folder_duplicates_request_from_dict = FindMessageFolderDuplicatesRequest.from_dict(find_message_folder_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


