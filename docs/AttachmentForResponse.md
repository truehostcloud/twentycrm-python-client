# AttachmentForResponse

An attachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**name** | **str** | Attachment name | [optional] 
**file** | [**List[AttachmentForResponseFileInner]**](AttachmentForResponseFileInner.md) | Attachment file | [optional] 
**full_path** | **str** | Attachment full path | [optional] 
**file_category** | **str** | Attachment file category | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**target_note** | **str** | Attachment target | [optional] 
**target_task** | **str** | Attachment target | [optional] 
**target_person** | **str** | Attachment target | [optional] 
**target_company** | **str** | Attachment target | [optional] 
**target_opportunity** | **str** | Attachment target | [optional] 
**target_dashboard** | **str** | Attachment target | [optional] 
**target_workflow** | **str** | Attachment target | [optional] 

## Example

```python
from twentycrm_client.models.attachment_for_response import AttachmentForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of AttachmentForResponse from a JSON string
attachment_for_response_instance = AttachmentForResponse.from_json(json)
# print the JSON string representation of the object
print(AttachmentForResponse.to_json())

# convert the object into a dict
attachment_for_response_dict = attachment_for_response_instance.to_dict()
# create an instance of AttachmentForResponse from a dict
attachment_for_response_from_dict = AttachmentForResponse.from_dict(attachment_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


