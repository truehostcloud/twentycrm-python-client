# FindAttachmentDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[Attachment]**](Attachment.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_attachment_duplicates_request import FindAttachmentDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindAttachmentDuplicatesRequest from a JSON string
find_attachment_duplicates_request_instance = FindAttachmentDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindAttachmentDuplicatesRequest.to_json())

# convert the object into a dict
find_attachment_duplicates_request_dict = find_attachment_duplicates_request_instance.to_dict()
# create an instance of FindAttachmentDuplicatesRequest from a dict
find_attachment_duplicates_request_from_dict = FindAttachmentDuplicatesRequest.from_dict(find_attachment_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


