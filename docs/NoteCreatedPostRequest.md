# NoteCreatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**NoteCreatedPostRequestObjectMetadata**](NoteCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**NoteForResponse**](NoteForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.note_created_post_request import NoteCreatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of NoteCreatedPostRequest from a JSON string
note_created_post_request_instance = NoteCreatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(NoteCreatedPostRequest.to_json())

# convert the object into a dict
note_created_post_request_dict = note_created_post_request_instance.to_dict()
# create an instance of NoteCreatedPostRequest from a dict
note_created_post_request_from_dict = NoteCreatedPostRequest.from_dict(note_created_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


