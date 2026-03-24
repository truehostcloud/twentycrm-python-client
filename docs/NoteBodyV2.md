# NoteBodyV2

Note body

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**blocknote** | **str** |  | [optional] 
**markdown** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.note_body_v2 import NoteBodyV2

# TODO update the JSON string below
json = "{}"
# create an instance of NoteBodyV2 from a JSON string
note_body_v2_instance = NoteBodyV2.from_json(json)
# print the JSON string representation of the object
print(NoteBodyV2.to_json())

# convert the object into a dict
note_body_v2_dict = note_body_v2_instance.to_dict()
# create an instance of NoteBodyV2 from a dict
note_body_v2_from_dict = NoteBodyV2.from_dict(note_body_v2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


