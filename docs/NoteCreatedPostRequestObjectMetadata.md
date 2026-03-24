# NoteCreatedPostRequestObjectMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name_singular** | **str** |  | [optional] 

## Example

```python
from twentycrm_client.models.note_created_post_request_object_metadata import NoteCreatedPostRequestObjectMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of NoteCreatedPostRequestObjectMetadata from a JSON string
note_created_post_request_object_metadata_instance = NoteCreatedPostRequestObjectMetadata.from_json(json)
# print the JSON string representation of the object
print(NoteCreatedPostRequestObjectMetadata.to_json())

# convert the object into a dict
note_created_post_request_object_metadata_dict = note_created_post_request_object_metadata_instance.to_dict()
# create an instance of NoteCreatedPostRequestObjectMetadata from a dict
note_created_post_request_object_metadata_from_dict = NoteCreatedPostRequestObjectMetadata.from_dict(note_created_post_request_object_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


