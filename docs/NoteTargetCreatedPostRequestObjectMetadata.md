# NoteTargetCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.note_target_created_post_request_object_metadata import NoteTargetCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of NoteTargetCreatedPostRequestObjectMetadata from a JSON string
note_target_created_post_request_object_metadata_instance = NoteTargetCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(NoteTargetCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
note_target_created_post_request_object_metadata_dict = note_target_created_post_request_object_metadata_instance.to_dict()
# create an instance of NoteTargetCreatedPostRequestObjectMetadata from a dict
note_target_created_post_request_object_metadata_from_dict = NoteTargetCreatedPostRequestObjectMetadata.from_dict(note_target_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


