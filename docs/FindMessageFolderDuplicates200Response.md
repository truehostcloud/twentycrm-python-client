# FindMessageFolderDuplicates200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[FindMessageFolderDuplicates200ResponseDataInner]**](FindMessageFolderDuplicates200ResponseDataInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_message_folder_duplicates200_response import FindMessageFolderDuplicates200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindMessageFolderDuplicates200Response from a JSON string
find_message_folder_duplicates200_response_instance = FindMessageFolderDuplicates200Response.from_json(json)
# print the JSON string representation of the object
print(FindMessageFolderDuplicates200Response.to_json())

# convert the object into a dict
find_message_folder_duplicates200_response_dict = find_message_folder_duplicates200_response_instance.to_dict()
# create an instance of FindMessageFolderDuplicates200Response from a dict
find_message_folder_duplicates200_response_from_dict = FindMessageFolderDuplicates200Response.from_dict(find_message_folder_duplicates200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


