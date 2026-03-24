# NoteForUpdate

A note

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**position** | **float** | Note record position | [optional] 
**title** | **str** | Note title | [optional] 
**body_v2** | [**NoteBodyV2**](NoteBodyV2.md) |  | [optional] 
**created_by** | [**AttachmentCreatedBy**](AttachmentCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentUpdatedBy**](AttachmentUpdatedBy.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.note_for_update import NoteForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of NoteForUpdate from a JSON string
note_for_update_instance = NoteForUpdate.from_json(json)
# print the JSON string representation of the object
print(NoteForUpdate.to_json())

# convert the object into a dict
note_for_update_dict = note_for_update_instance.to_dict()
# create an instance of NoteForUpdate from a dict
note_for_update_from_dict = NoteForUpdate.from_dict(note_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


