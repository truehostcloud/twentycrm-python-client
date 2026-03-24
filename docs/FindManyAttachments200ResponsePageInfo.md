# FindManyAttachments200ResponsePageInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**has_next_page** | **bool** |  | [optional] 
**start_cursor** | **UUID** |  | [optional] 
**end_cursor** | **UUID** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_attachments200_response_page_info import FindManyAttachments200ResponsePageInfo

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyAttachments200ResponsePageInfo from a JSON string
find_many_attachments200_response_page_info_instance = FindManyAttachments200ResponsePageInfo.from_json(json)
# print the JSON string representation of the object
print(FindManyAttachments200ResponsePageInfo.to_json())

# convert the object into a dict
find_many_attachments200_response_page_info_dict = find_many_attachments200_response_page_info_instance.to_dict()
# create an instance of FindManyAttachments200ResponsePageInfo from a dict
find_many_attachments200_response_page_info_from_dict = FindManyAttachments200ResponsePageInfo.from_dict(find_many_attachments200_response_page_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


