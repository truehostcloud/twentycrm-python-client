# NoteTarget

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
from twentycrm_client.models.note_target import NoteTarget

# TODO update the JSON string below
json = "{}"
# create an instance of NoteTarget from a JSON string
note_target_instance = NoteTarget.from_json(json)
# print the JSON string representation of the object
print(NoteTarget.to_json())

# convert the object into a dict
note_target_dict = note_target_instance.to_dict()
# create an instance of NoteTarget from a dict
note_target_from_dict = NoteTarget.from_dict(note_target_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


