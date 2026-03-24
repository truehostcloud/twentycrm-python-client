# FindManyNoteTargets200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**note_targets** | [**List[NoteTargetForResponse]**](NoteTargetForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.find_many_note_targets200_response_data import FindManyNoteTargets200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of FindManyNoteTargets200ResponseData from a JSON string
find_many_note_targets200_response_data_instance = FindManyNoteTargets200ResponseData.from_json(json)
# print the JSON string representation of the object
print(FindManyNoteTargets200ResponseData.to_json())

# convert the object into a dict
find_many_note_targets200_response_data_dict = find_many_note_targets200_response_data_instance.to_dict()
# create an instance of FindManyNoteTargets200ResponseData from a dict
find_many_note_targets200_response_data_from_dict = FindManyNoteTargets200ResponseData.from_dict(find_many_note_targets200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


