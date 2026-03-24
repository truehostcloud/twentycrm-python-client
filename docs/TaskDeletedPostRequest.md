# TaskDeletedPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_url** | **str** |  | [optional] 
**event_name** | **str** |  | [optional] 
**object_metadata** | [**TaskCreatedPostRequestObjectMetadata**](TaskCreatedPostRequestObjectMetadata.md) |  | [optional] 
**workspace_id** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**workspace_member_id** | **str** |  | [optional] 
**webhook_id** | **str** |  | [optional] 
**event_date** | **str** |  | [optional] 
**record** | [**TaskForResponse**](TaskForResponse.md) |  | [optional] 

## Example

```python
from twentycrm_client.models.task_deleted_post_request import TaskDeletedPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of TaskDeletedPostRequest from a JSON string
task_deleted_post_request_instance = TaskDeletedPostRequest.from_json(json)
# print the JSON string representation of the object
print(TaskDeletedPostRequest.to_json())

# convert the object into a dict
task_deleted_post_request_dict = task_deleted_post_request_instance.to_dict()
# create an instance of TaskDeletedPostRequest from a dict
task_deleted_post_request_from_dict = TaskDeletedPostRequest.from_dict(task_deleted_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


