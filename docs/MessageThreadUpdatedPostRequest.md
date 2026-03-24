# MessageThreadUpdatedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**MessageThreadCreatedPostRequestObjectMetadata**](MessageThreadCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**MessageThreadForResponse**](MessageThreadForResponse.md) |  | [optional] 
**updated_fields** | **List[str]** |  | [optional] 

## Example

```python
from twentycrm_client.models.message_thread_updated_post_request import MessageThreadUpdatedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of MessageThreadUpdatedPostRequest from a JSON string
message_thread_updated_post_request_instance = MessageThreadUpdatedPostRequest.from_json(json)
# print the JSON string representation of the object
print(MessageThreadUpdatedPostRequest.to_json())

# convert the object into a dict
message_thread_updated_post_request_dict = message_thread_updated_post_request_instance.to_dict()
# create an instance of MessageThreadUpdatedPostRequest from a dict
message_thread_updated_post_request_from_dict = MessageThreadUpdatedPostRequest.from_dict(message_thread_updated_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


