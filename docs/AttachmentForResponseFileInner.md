# AttachmentForResponseFileInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **UUID** |  | [optional] 
**label** | **str** |  | [optional] 
**extension** | **str** |  | [optional] 
**url** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.attachment_for_response_file_inner import AttachmentForResponseFileInner

# TODO update the JSON string below
json = "{}"
# create an instance of AttachmentForResponseFileInner from a JSON string
attachment_for_response_file_inner_instance = AttachmentForResponseFileInner.from_json(json)
# print the JSON string representation of the object
print(AttachmentForResponseFileInner.to_json())

# convert the object into a dict
attachment_for_response_file_inner_dict = attachment_for_response_file_inner_instance.to_dict()
# create an instance of AttachmentForResponseFileInner from a dict
attachment_for_response_file_inner_from_dict = AttachmentForResponseFileInner.from_dict(attachment_for_response_file_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


