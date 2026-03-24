# AttachmentForResponseUpdatedBy

The workspace member who last updated the record

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | [optional] 
**workspace_member_id** | **UUID** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.attachment_for_response_updated_by import AttachmentForResponseUpdatedBy

# TODO update the JSON string below
json = "{}"
# create an instance of AttachmentForResponseUpdatedBy from a JSON string
attachment_for_response_updated_by_instance = AttachmentForResponseUpdatedBy.from_json(json)
# print the JSON string representation of the object
print(AttachmentForResponseUpdatedBy.to_json())

# convert the object into a dict
attachment_for_response_updated_by_dict = attachment_for_response_updated_by_instance.to_dict()
# create an instance of AttachmentForResponseUpdatedBy from a dict
attachment_for_response_updated_by_from_dict = AttachmentForResponseUpdatedBy.from_dict(attachment_for_response_updated_by_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


