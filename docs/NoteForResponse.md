# NoteForResponse

A note

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**position** | **float** | Note record position | [optional] 
**title** | **str** | Note title | [optional] 
**body_v2** | [**NoteBodyV2**](NoteBodyV2.md) |  | [optional] 
**created_by** | [**AttachmentForResponseCreatedBy**](AttachmentForResponseCreatedBy.md) |  | [optional] 
**updated_by** | [**AttachmentForResponseUpdatedBy**](AttachmentForResponseUpdatedBy.md) |  | [optional] 
**attachments** | [**List[AttachmentForResponse]**](AttachmentForResponse.md) | Note attachments | [optional] 
**favorites** | [**List[FavoriteForResponse]**](FavoriteForResponse.md) | Favorites linked to the note | [optional] 
**note_targets** | [**List[NoteTargetForResponse]**](NoteTargetForResponse.md) | Note targets | [optional] 
**timeline_activities** | [**List[TimelineActivityForResponse]**](TimelineActivityForResponse.md) | Timeline Activities linked to the note. | [optional] 

## Example

```python
from twentycrm_client.models.note_for_response import NoteForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of NoteForResponse from a JSON string
note_for_response_instance = NoteForResponse.from_json(json)
# print the JSON string representation of the object
print(NoteForResponse.to_json())

# convert the object into a dict
note_for_response_dict = note_for_response_instance.to_dict()
# create an instance of NoteForResponse from a dict
note_for_response_from_dict = NoteForResponse.from_dict(note_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


