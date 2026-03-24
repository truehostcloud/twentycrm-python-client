# NoteTargetForResponse

A note target

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **UUID** | Id | [optional] 
**created_at** | **datetime** | Creation date | [optional] 
**updated_at** | **datetime** | Last time the record was changed | [optional] 
**deleted_at** | **datetime** | Date when the record was deleted | [optional] 
**target_company** | **str** | NoteTarget target | [optional] 
**note_id** | **UUID** |  | [optional] 
**target_person** | **str** | NoteTarget target | [optional] 
**target_opportunity** | **str** | NoteTarget target | [optional] 
**note** | [**NoteForResponse**](NoteForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.note_target_for_response import NoteTargetForResponse

# TODO update the JSON string below
json = "{}"
# create an instance of NoteTargetForResponse from a JSON string
note_target_for_response_instance = NoteTargetForResponse.from_json(json)
# print the JSON string representation of the object
print(NoteTargetForResponse.to_json())

# convert the object into a dict
note_target_for_response_dict = note_target_for_response_instance.to_dict()
# create an instance of NoteTargetForResponse from a dict
note_target_for_response_from_dict = NoteTargetForResponse.from_dict(note_target_for_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


