# NoteTargetForUpdate

A note target

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_company** | **str** | NoteTarget target | [optional] 
**note_id** | **UUID** |  | [optional] 
**target_person** | **str** | NoteTarget target | [optional] 
**target_opportunity** | **str** | NoteTarget target | [optional] 

## Example

```python
from twentycrm_client.models.note_target_for_update import NoteTargetForUpdate

# TODO update the JSON string below
json = "{}"
# create an instance of NoteTargetForUpdate from a JSON string
note_target_for_update_instance = NoteTargetForUpdate.from_json(json)
# print the JSON string representation of the object
print(NoteTargetForUpdate.to_json())

# convert the object into a dict
note_target_for_update_dict = note_target_for_update_instance.to_dict()
# create an instance of NoteTargetForUpdate from a dict
note_target_for_update_from_dict = NoteTargetForUpdate.from_dict(note_target_for_update_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


