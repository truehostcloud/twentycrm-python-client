# FindNoteTargetDuplicatesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[NoteTarget]**](NoteTarget.md) |  | [optional] 
**ids** | **List[UUID]** |  | [optional] 

## Example

```python
from twentycrm_client.models.find_note_target_duplicates_request import FindNoteTargetDuplicatesRequest

# TODO update the JSON string below
json = "{}"
# create an instance of FindNoteTargetDuplicatesRequest from a JSON string
find_note_target_duplicates_request_instance = FindNoteTargetDuplicatesRequest.from_json(json)
# print the JSON string representation of the object
print(FindNoteTargetDuplicatesRequest.to_json())

# convert the object into a dict
find_note_target_duplicates_request_dict = find_note_target_duplicates_request_instance.to_dict()
# create an instance of FindNoteTargetDuplicatesRequest from a dict
find_note_target_duplicates_request_from_dict = FindNoteTargetDuplicatesRequest.from_dict(find_note_target_duplicates_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


