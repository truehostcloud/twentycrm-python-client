# AttachmentFileInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **UUID** |  | [optional] 
**label** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.attachment_file_inner import AttachmentFileInner

# TODO update the JSON string below
json = "{}"
# create an instance of AttachmentFileInner from a JSON string
attachment_file_inner_instance = AttachmentFileInner.from_json(json)
# print the JSON string representation of the object
print(AttachmentFileInner.to_json())

# convert the object into a dict
attachment_file_inner_dict = attachment_file_inner_instance.to_dict()
# create an instance of AttachmentFileInner from a dict
attachment_file_inner_from_dict = AttachmentFileInner.from_dict(attachment_file_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


