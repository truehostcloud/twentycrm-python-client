# NoteTargetCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**NoteTargetCreatedPostRequestObjectMetadata**](NoteTargetCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**NoteTargetForResponse**](NoteTargetForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.note_target_created_post_request import NoteTargetCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of NoteTargetCreatedPostRequest from a JSON string
note_target_created_post_request_instance = NoteTargetCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(NoteTargetCreatedPostRequest.to_json())

# convert the object into a dict
note_target_created_post_request_dict = note_target_created_post_request_instance.to_dict()
# create an instance of NoteTargetCreatedPostRequest from a dict
note_target_created_post_request_from_dict = NoteTargetCreatedPostRequest.from_dict(note_target_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


