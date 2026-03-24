# Attachment

An attachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Attachment name | [optional] 
**file** | [**List[AttachmentFileInner]**](AttachmentFileInner.md) | Attachment file | [optional] 
**full_path** | **str** | Attachment full path | [optional] 
**file_category** | **str** | Attachment file category | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 
**target_note** | **str** | Attachment target | [optional] 
**target_task** | **str** | Attachment target | [optional] 
**target_person** | **str** | Attachment target | [optional] 
**target_company** | **str** | Attachment target | [optional] 
**target_opportunity** | **str** | Attachment target | [optional] 
**target_dashboard** | **str** | Attachment target | [optional] 
**target_workflow** | **str** | Attachment target | [optional] 

## Example

```python
from twentycrm_client.models.attachment import Attachment

# TODO update the JSON string below
json = "{}"
# create an instance of Attachment from a JSON string
attachment_instance = Attachment.from_json(json)
# print the JSON string representation of the object
print(Attachment.to_json())

# convert the object into a dict
attachment_dict = attachment_instance.to_dict()
# create an instance of Attachment from a dict
attachment_from_dict = Attachment.from_dict(attachment_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


