# TaskTargetDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**TaskTargetCreatedPostRequestObjectMetadata**](TaskTargetCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**TaskTargetForResponse**](TaskTargetForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.task_target_deleted_post_request import TaskTargetDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of TaskTargetDeletedPostRequest from a JSON string
task_target_deleted_post_request_instance = TaskTargetDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(TaskTargetDeletedPostRequest.to_json())

# convert the object into a dict
task_target_deleted_post_request_dict = task_target_deleted_post_request_instance.to_dict()
# create an instance of TaskTargetDeletedPostRequest from a dict
task_target_deleted_post_request_from_dict = TaskTargetDeletedPostRequest.from_dict(task_target_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


