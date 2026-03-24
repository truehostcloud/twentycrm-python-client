# DeleteManyNoteTargets200ResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delete_note_targets** | [**List[DeleteManyAttachments200ResponseDataDeleteAttachmentsInner]**](DeleteManyAttachments200ResponseDataDeleteAttachmentsInner.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.delete_many_note_targets200_response_data import DeleteManyNoteTargets200ResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of DeleteManyNoteTargets200ResponseData from a JSON string
delete_many_note_targets200_response_data_instance = DeleteManyNoteTargets200ResponseData.from_json(json)
# print the JSON string representation of the object
print(DeleteManyNoteTargets200ResponseData.to_json())

# convert the object into a dict
delete_many_note_targets200_response_data_dict = delete_many_note_targets200_response_data_instance.to_dict()
# create an instance of DeleteManyNoteTargets200ResponseData from a dict
delete_many_note_targets200_response_data_from_dict = DeleteManyNoteTargets200ResponseData.from_dict(delete_many_note_targets200_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


