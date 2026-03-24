# FindAttachmentDuplicates200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[FindAttachmentDuplicates200ResponseDataInner]**](FindAttachmentDuplicates200ResponseDataInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_attachment_duplicates200_response import FindAttachmentDuplicates200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FindAttachmentDuplicates200Response from a JSON string
find_attachment_duplicates200_response_instance = FindAttachmentDuplicates200Response.from_json(json)
# print the JSON string representation of the object
print(FindAttachmentDuplicates200Response.to_json())

# convert the object into a dict
find_attachment_duplicates200_response_dict = find_attachment_duplicates200_response_instance.to_dict()
# create an instance of FindAttachmentDuplicates200Response from a dict
find_attachment_duplicates200_response_from_dict = FindAttachmentDuplicates200Response.from_dict(find_attachment_duplicates200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


